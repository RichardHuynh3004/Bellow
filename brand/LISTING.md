# Marketplace listing — copy/paste source

App: **Blocked Aging for Jira** · Vendor: **Bellowsware**
App id: `053513c8-d15a-4b48-9cfd-c422727e0bcc`

---

## Name
```
Blocked Aging
```

## App key
```
053513c8-d15a-4b48-9cfd-c422727e0bcc
```
Full ARI: `ari:cloud:ecosystem::app/053513c8-d15a-4b48-9cfd-c422727e0bcc`

## Tagline  (88/130)
```
See which work items are stuck, how long each has been stuck, and who is holding them up
```
Must be a phrase, and must NOT end with punctuation.

## Summary  (248/250)
```
See every work item that is flagged or waiting on an unresolved blocker, ordered by how long it has been stuck. Group by blocker to find the one thing holding up four others. Read-only, and runs entirely inside Atlassian — nothing leaves your site.
```

## More details  (997/1000)
```
A flag on a Jira card looks the same whether it went up yesterday or last quarter. Blocked Aging shows the difference.

Every stuck work item lands on one dashboard gadget, ordered by how long it has really been waiting.

WHAT COUNTS AS BLOCKED
The item is flagged, or linked to a blocker that is not yet Done. A completed blocker stops counting, so stale links no longer inflate the list.

HOW THE AGE IS MEASURED
From the start of the current unbroken blocked period, not the most recent event. Flagged Monday and link-blocked Friday means stuck since Monday. Unblocked in between restarts the clock. Where history cannot prove when the stretch began, it says "unknown" instead of inventing a number.

GROUP BY BLOCKER
One button flips the table: instead of what is stuck, see who is holding things up. One contract blocking four items is one conversation, not four.

PRIVACY
Read-only, one scope, nothing written back. It runs on Atlassian infrastructure — there is nowhere for your data to go.
```

## Categories
```
Dashboard gadgets
Reports
Project management
```
Do NOT pick "Time tracking" — people browsing it want worklogs and timesheets,
so it draws installs that uninstall and leave low ratings. With zero reviews,
one bad rating costs more than the extra views are worth. Same reasoning rules
out "IT & helpdesk", which is JSM territory.

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
Bellowsware
```
**Description**
```
Bellowsware builds small, focused apps for Jira and Confluence.

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

---

## Version / release fields

**Release summary** (78/80)
```
Which work items are stuck, how long they have been stuck, and who is blocking
```

**Release notes** (976/1000)
```
First public release.

WHAT IT DOES
Shows every blocked work item on one dashboard gadget, ordered by how long each has actually been waiting.

An item counts as blocked when it is flagged, or linked to a blocker that is not yet Done. A blocker already completed stops counting, so stale links do not inflate the list.

The age is measured from the start of the current unbroken blocked period, not the most recent event. Where history cannot prove when that period began, the gadget reports "unknown" instead of guessing.

ALSO IN THIS RELEASE
- Group by blocker: see which single issue is holding up the most work
- Sort on any column, with issue keys sorting numerically
- Three severity levels: items turn amber before they turn red
- Hover any age to see the exact date the current stretch began
- Manual refresh with a last-updated timestamp

PERMISSIONS
Read-only. One scope, read:jira-work. Nothing is written back to Jira, and no data leaves Atlassian infrastructure.
```

**License**
```
Free
```
Ship the first version free. The moat on this Marketplace is review count, and a
free app collects installs and ratings far faster than a paid one. Turn licensing
on later, once there are reviews to convert against.

**Documentation URL**
```
https://github.com/RichardHuynh3004/Bellow/blob/main/brand/DOCUMENTATION.md
```

**Use a standard agreement as your EULA?**
```
Yes
```
Use Atlassian's standard End User Agreement. Do not write a custom one — it needs
legal review you do not need to pay for, and Appsvio recently moved off their own
custom EULA onto this exact standard agreement.

**Privacy policy URL**
```
https://github.com/RichardHuynh3004/Bellow/blob/main/brand/PRIVACY.md
```

---

## Highlight captions (separate field from description)

1. `The gadget on a Jira dashboard: eight blocked items ordered by how long each has been waiting, with the overdue ones in red`
2. `The same items grouped by blocker, showing one unresolved issue holding up three others`
3. `The edit screen: one JQL filter to set the scope, one number to set when an item counts as overdue`
