# Homepage — Engineering Charter

This project follows Company Knowledge (OKF bundle at /Volumes/KINGSTON/OKF). No exceptions.

## Before architecting or implementing
1. Read /standards/index.md — architecture, delivery, ways-of-working, testing, documentation.
2. Read this project's profile: /projects/homepage.md

## While working
- Keep docs/plan.md current.
- Record non-obvious or costly-to-reverse decisions as ADRs in docs/decisions/
  (template: docs/decisions/0000-adr-template.md). Follow /standards/decision-records.md.
- This repo is a single static `index.html` — no build step, no framework. Don't introduce
  either without a good reason (record it as an ADR if you do).

## Definition of Done
Enforce the shared gate in /standards/ways-of-working.md before calling anything done.
