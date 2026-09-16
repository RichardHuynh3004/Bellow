# Marketplace listing — copy/paste source

App: **Blocked Aging for Jira** · Vendor: **Bellows**
App id: `053513c8-d15a-4b48-9cfd-c422727e0bcc`

---

## Name
```
Blocked Aging
```

## Summary (short line under the name)
```
See which work items are stuck, and how long they have been stuck.
```

## Description
```
Jira tells you what is blocked. It does not tell you what has been blocked
for six weeks.

Blocked Aging puts every stuck work item on one dashboard gadget, ordered by
how long it has actually been waiting — so the oldest problem is always at
the top instead of buried on a board.

WHAT COUNTS AS BLOCKED
· The item is flagged
· The item is linked to a blocker that is not Done

A blocker that has already been completed no longer counts, so stale links
stop inflating your list.

HOW LONG IT HAS BEEN STUCK
The age is measured from the start of the current unbroken blocked period.
An item flagged on Monday and additionally link-blocked on Friday has been
stuck since Monday. One that was unblocked in between starts again from
Friday. Where the history no longer reaches back far enough, we say
"unknown" rather than invent a number.

GROUP BY BLOCKER
Flip the table around to see who is holding things up. If one unsigned
contract is blocking four items, that is one conversation, not four.

PRIVACY
Read-only. Bellows requests a single scope, read:jira-work, and writes
nothing back to Jira. All processing happens inside Atlassian's
infrastructure — your data never reaches our servers, because we do not
run any.
```

---

## Highlight 1
**Title** (≤50)
```
See what is stuck, and for how long
```
**Summary / caption** (≤220)
```
Every blocked work item on one gadget, oldest first. The item that has been
waiting longest is always at the top, not buried three columns deep on a board.
```
Screenshot: the main table, 8 rows visible.

## Highlight 2
**Title**
```
Find the bottleneck, not just the symptoms
```
**Summary / caption**
```
Flip the table to see who is holding things up. One unsigned contract blocking
four items is one conversation, not four separate chases.
```
Screenshot: the gadget after pressing "Group by blocker".

## Highlight 3
**Title**
```
Scope it to your team in one field
```
**Summary / caption**
```
Point it at any JQL filter and set when an item counts as overdue. Nothing else
to configure, and nothing written back to Jira.
```
Screenshot: the gadget's Edit screen.

---

## Support

**Email**
```
support@bellowsware.com
```

**Support hours**
```
Monday to Friday, 09:00–18:00 (UTC+7)
```

**Support policy**
```
We reply to every request within 1 business day.

Our team works UTC+7, so a ticket raised during North American or European
business hours is typically answered the following morning your time.
Critical issues affecting a production instance are picked up as soon as
we are online, including outside listed hours.

We do not offer phone or live chat support.
```

---

## Vendor profile

**Name**
```
Bellows
```
**Description**
```
Bellows builds small, focused apps for Jira and Confluence.

Each app does one job well and runs entirely on Atlassian infrastructure —
no external servers, no data leaving your instance.
```

---

## Legal

| Field | Value |
|---|---|
| End User Agreement | **Use Atlassian's Standard End User Agreement** — do not write a custom one |
| Privacy policy URL | https://github.com/RichardHuynh3004/Bellow/blob/main/brand/PRIVACY.md |
| DPA | Not required: no personal data is processed outside Atlassian |
| Scopes to declare | `read:jira-work` only |
| Remote hostnames | **None** — this is what earns "Runs on Atlassian" |

## Assets

| Field | File |
|---|---|
| App logo 144×144 | `brand/logo-144.png` |
| Banner 1120×548 | `brand/banner-1120x548.png` |
| Banner 560×274 | `brand/banner-560x274.png` |
| Gadget thumbnail | already in manifest, served from this repo |

Highlight screenshots must be supplied at 1840×900 (full) and 580×330 (cropped).
