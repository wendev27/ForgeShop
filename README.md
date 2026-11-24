# ForgeShop

A small e-commerce app built to practice and prove an end-to-end delivery
pipeline: from `git push` to a tested, security-scanned, monitored
deployment on AWS.

The shop is deliberately simple. The engineering around it is the point.

> Status: early development. The Evidence section lists only what has been
> built and can be verified.

## Why this exists

I'm a student engineer building toward DevOps and DevSecOps roles. I wanted
one project where I play both parts: the developer who ships small features,
and the DevOps engineer who builds the system that tests, secures, deploys,
and monitors them.

## Focus areas

- Fullstack: a small, working storefront and API
- DevOps: infrastructure as code, CI/CD, deployment, monitoring
- Security: threat checks per feature, abuse-case tests, pipeline scanning
- QA automation: API and end-to-end tests, bug reports, regression tests

## Scope (frozen)

In: user registration and login, roles (customer/admin), product browsing,
cart, checkout, order history, admin product management.

Out: inventory, search, reviews, coupons, shipping, emails, custom design.

New features exist only to exercise the pipeline. Every feature ships with
tests and a documented security check.

## How features get built

1. Acceptance criteria and abuse cases are written in the issue.
2. The feature is built with unit and API tests alongside it.
3. Abuse-case tests are added (for example: access to another user's order).
4. The pull request must show passing checks before merge.
5. Every bug found gets a regression test before the fix.

## Stack

TypeScript, Node.js, React, PostgreSQL, Docker, GitHub Actions, Terraform, AWS.
Other tools are added to the docs only when they are actually adopted.

## Evidence

Nothing is listed here until it can be linked.

| Area | What was built | Proof |
| ---- | -------------- | ----- |

## Decisions

Short architecture decision records live in /docs/adr.

## Roadmap

Tracked in GitHub Issues.

## Author

Mark Wendell Aquino - wendev.app - github.com/wendev27
