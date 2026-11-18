# Security Policy — TimeBill

> Last updated: 2026-11-18

## Supported product

FlowLens Charts: Time in Status, Cycle Time, WIP (Atlassian Forge app).

## Reporting a vulnerability

Found a security issue? Email **security@prismblk.com** — please include reproduction steps and, where possible, a proof of concept. We aim to acknowledge reports within 24 hours (Mon–Fri) and will keep you updated on fix progress.

We ask that you give us a reasonable window to remediate before public disclosure.

## Scope

- The Forge app backend (resolvers, scheduled triggers) and frontend as deployed to production
- Our handling of Atlassian site data via official Forge APIs

Out of scope: the Atlassian Forge platform itself (report to Atlassian), and issues requiring compromised admin credentials on your own site.

## How we handle data

FlowLens runs entirely on Atlassian Forge: issue and changelog data are read via official Jira APIs, and the chart index is stored in Forge storage scoped to your site. We operate no external servers and ship no third-party analytics. See our Privacy Policy for details.

## Cryptography & storage

All data at rest is stored in Atlassian-managed Forge storage; transport uses TLS via the Forge platform. We store no credentials — the app acts under Atlassian's managed authentication.
