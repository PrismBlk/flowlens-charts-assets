# Privacy Policy — FlowLens Charts

> Last updated: 2026-10-11
> 用途：Marketplace 审核要求的隐私政策页（英文原文，GitHub Pages 托管后的公开版本）。

FlowLens Charts ("the app", "we") is an Atlassian Forge app that renders agile flow charts on Jira dashboards. This policy explains what data the app processes and how.

## What we collect

**Nothing.** FlowLens has no accounts, no sign-up, no analytics, no third-party services, and no database of our own. The app does not collect, transmit, or store any personal data outside your Atlassian site.

## What the app reads

When you use FlowLens, the app reads a limited set of Jira issue data **through Atlassian's official APIs, within your own site**:

- Issue metadata: created/resolved dates, status and status change history (changelog), sprint membership, story point values, project keys
- The purpose is solely to compute the charts you configure (e.g., time in status, cycle time)

Access is read-only. The app cannot modify, create or delete your Jira issues.

## Where data is stored

- **Live widgets** (free tier) fetch data on demand and store nothing.
- **Indexed widgets** (Pro tier) store computed aggregates (status intervals per issue) in **Atlassian Forge storage**, which is hosted by Atlassian inside the Forge platform. This data is scoped to your site's installation of the app and is never transferred to us or any third party.
- You can stop all processing at any time by uninstalling the app, which deletes all associated Forge storage.

## Permissions

The app requests the minimum Atlassian scopes required: read access to Jira work data (`read:jira-work`) and app storage. It requests no write access to your issues, no user profile data, and no admin permissions.

## Third parties

None. No external API calls, no analytics or tracking SDKs, no advertising, no cookies beyond what the Atlassian platform itself requires.

## GDPR & CCPA

Because we collect no personal data and all processing happens inside the Atlassian platform under your Atlassian agreement, FlowLens adds no additional data-processing surface. Data subject requests should be handled through your Atlassian site administration; uninstalling the app removes all app data.

## Contact

Questions about this policy: **prismblk@gmail.com** (replace with your support email before listing)

## Changes

We will update this page if the app's data handling changes. Material changes will be reflected in an app release note.
