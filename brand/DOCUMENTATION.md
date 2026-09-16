# Blocked Aging for Jira — documentation

A Jira dashboard gadget that shows which work items are stuck, how long each has
been stuck, and who is holding them up.

---

## Install

1. In Jira, open **Dashboards** and create or open a dashboard
2. Select **Add gadget**
3. Find **Blocked Aging** and select **Add**
4. On the gadget, open the **•••** menu and select **Edit**

## Configure

| Field | What it does |
|---|---|
| **Filter (JQL)** | The scope the gadget watches. Required. Must be scoped — for example `project = ABC AND resolution = EMPTY` |
| **Overdue after (days)** | Items blocked longer than this turn red. Items past 60% of it turn amber. Default is 5 |

Jira rejects unscoped JQL from apps, so the filter must contain a clause such as
`project`, `key`, `filter`, `assignee` or `sprint`. The gadget tells you if the
filter is too broad before it saves.

## What counts as blocked

An item appears when either is true:

- it is **flagged**, or
- it is linked to a blocker (`is blocked by`) that is **not yet Done**

A blocker that has already been completed stops counting straight away, so a
stale link left behind after the work finished will not keep an item on the list.

Items that are *doing* the blocking do not appear — only the ones that are stuck.

## How the age is measured

From the start of the **current unbroken blocked period**, not from the most
recent blocking event.

- Flagged on Monday, link-blocked on Friday, never unflagged → stuck since **Monday**
- Flagged Monday, unflagged Wednesday, link-blocked Friday → stuck since **Friday**

Where the issue history no longer reaches far enough back to prove when the
current stretch began, the gadget shows **unknown** rather than inventing a
number. Unknown rows always sort last.

Hover the age to see the exact date and time the current stretch began.

## Group by blocker

Select **Group by blocker** to flip the table: one section per blocker, busiest
first, so a single issue holding up four others is visible as one row to chase
instead of four separate ones.

An item waiting on two blockers appears under both, because clearing either one
unsticks it. Items that are only flagged, with no linked blocker, are collected
under **Flagged, no linked blocker** — they are stuck but have nobody recorded to
chase.

## Sorting

Every column sorts. The gadget opens sorted by age, longest first. Issue keys
sort numerically, so KAN-2 comes before KAN-11.

## Refreshing

Jira does not reload a gadget on its own. Use **Refresh** on the gadget to fetch
current data; the toolbar shows when the data was last loaded.

## Limits

- A refresh reads at most **100 matching items**. If your filter matches more,
  the gadget says so rather than silently showing a partial list — narrow the
  filter.
- Each blocked item costs one history lookup, so a very large filter is slower.

## Permissions and data

The app requests one scope, `read:jira-work`, and writes nothing back to Jira. It
runs entirely on Atlassian infrastructure and qualifies for **Runs on Atlassian**:
no external servers, no third parties, no analytics. You never see a work item
through this gadget that you could not already see in Jira.

## Support

**support@bellowsware.com** — Monday to Friday, 09:00–18:00 (UTC+7).
We reply to every request within one business day.
