# Privacy Policy — Blocked Aging for Jira

**Vendor:** Bellowsware
**Contact:** support@bellowsware.com
**Last updated:** 16 September 2026

## The short version

Blocked Aging does not collect, store, or transmit your data. It cannot: the app
has no servers.

## Where the app runs

Blocked Aging is a Forge app and qualifies for Atlassian's **Runs on Atlassian**
programme. All of its code executes inside Atlassian's own cloud infrastructure,
in your instance's region. Bellowsware operates no servers, no database, and no
analytics endpoint that your data could reach.

## What the app reads

The app requests a single permission scope:

| Scope | Why |
|---|---|
| `read:jira-work` | To read the work items matching the filter you configure, their flags, their issue links, and their change history |

It reads this data only while rendering the gadget, in response to your own
request, and using your own Jira permissions. You never see a work item through
this gadget that you could not already see in Jira.

## What the app writes

Nothing. The app holds no write scope. It cannot create, edit, flag, transition,
comment on, or delete anything in Jira.

## What the app stores

Nothing. Results are computed on each load and discarded. There is no database,
no cache, and no log of your work items outside Atlassian's own platform logging.

The only value the app persists is the gadget's own configuration — your JQL
filter and your overdue threshold — which Atlassian stores with the dashboard, in
your instance, not with us.

## Third parties

There are none. The app makes no network calls outside the Atlassian platform. No
advertising, no tracking, no third-party analytics, no AI or LLM processing of
your content.

## Sub-processors

None.

## Data retention and deletion

Because nothing is stored outside your instance, there is nothing for us to
retain or delete. Uninstalling the app removes it completely; the gadget
configuration is removed by Atlassian with the dashboard item.

## Support requests

If you email support@bellowsware.com, we hold that email and anything you choose
to include in it, in our mailbox, for as long as needed to resolve the issue.
Please do not paste sensitive work item content into a support request — a screen
recording or an issue key is usually enough.

## Changes

If this policy changes, the updated version will be published at this URL with a
new date. Material changes will also be noted in the app's Marketplace release
notes.

## Questions

support@bellowsware.com — we reply within one business day (UTC+7).
