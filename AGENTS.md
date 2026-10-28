# Homepage — Engineering Charter

The live marketing site for Appercut Development at appercutdevelopment.com: one static
`index.html` with inline CSS, served by GitHub Pages. A push to `main` deploys it.

## Before architecting or implementing
Read, in order: README.md, docs/plan.md, docs/decisions/ (the ADRs).

## While working
- **Story first.** Every slice starts from a GitHub story issue. Every PR says `Closes #<story>` or
  `Contributes to #<story>`. Agents open PRs; they never merge them and never push to `main`.
- **Commits:** Conventional Commits whose body explains why. No AI or tool attribution.
- This repo is a single static `index.html` — no build step, no framework. Don't introduce
  either without a good reason (record it as an ADR if you do).
- **Plan and decisions:** keep docs/plan.md current. Record non-obvious or costly-to-reverse
  decisions as ADRs in docs/decisions/ (template: docs/decisions/0000-adr-template.md).
- **Docs** change in the same PR as the code, describe the system as it is, and say "the user", not
  a person's name.
- **The user decides.** Present evidence and a recommendation. Never round an unchecked box up to
  "done".

## Definition of Done
- [ ] Rules followed, or the deviation recorded as an ADR
- [ ] The page checked in a browser (there is no build or test step)
- [ ] Docs current; real decisions recorded
- [ ] Anything surprising is written down (ADR or the PR's Lessons line)
