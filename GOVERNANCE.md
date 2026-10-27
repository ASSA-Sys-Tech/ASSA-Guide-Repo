# Governance

This project uses a **maintainer / meritocracy model**: a small group of trusted maintainers has authority over day-to-day technical and content decisions, new maintainers are added based on demonstrated contribution, and the ASSA Systems & Technology committee holds a lightweight backstop role for matters affecting the Society's name and reputation.

## Roles

### Contributors
Anyone who opens an issue, submits a pull request, or lists a tool in the registry. No formal status required — this is the entry point for everyone.

### Maintainers
Contributors who have been granted merge (write) access to this repository. Maintainers:
- Review and merge pull requests
- Triage and respond to issues
- Vote on governance decisions described below
- Decide whether a proposed new package belongs under `/packages`
- Help contributors who are new to the PR/GitHub process

**Current maintainers** are listed in `MAINTAINERS.md`.

### The ASSA Systems & Technology Committee (backstop role)
The committee does not make day-to-day technical decisions. Its role is limited to:
- Appointing the *initial* set of maintainers at project launch
- Serving as final escalation point if maintainers reach deadlock on a governance question (see below)
- Stepping in on matters of Society reputation — e.g., if hosted content is legally or professionally problematic in a way that affects ASSA's name, regardless of the technical merits
- Periodically (annually) reviewing that the maintainer group remains active and reasonably representative of the community

## How someone becomes a maintainer

1. A contributor has had **three or more substantive pull requests merged** (substantive = meaningful content, not just typo fixes), demonstrating sound judgment and reliable follow-through.
2. Any existing maintainer nominates them, publicly, via an issue tagged `governance`.
3. Existing maintainers have **two weeks** to raise objections. Silence is treated as support.
4. If no unresolved objection remains after two weeks, the nominee is added as a maintainer.

This mirrors how most established open-source communities do it (including other actuarial open-source projects) — access is earned through visible, reviewed work rather than granted upfront, which keeps trust calibrated to actual track record.

## How decisions get made

- **Routine decisions** (merging a PR, responding to an issue, minor scope calls): any individual maintainer can act unilaterally.
- **Non-routine decisions** (adding a new package to the org, removing a maintainer, changing this governance document, changing the license): require a **simple majority vote among active maintainers**, conducted transparently in a tagged `governance` issue, open for at least one week.
- **Deadlock**: if maintainers cannot reach a majority after reasonable discussion, the question is escalated to the Systems & Technology committee for a final decision.

## Removing a maintainer

Maintainer status can be removed by majority vote of the other maintainers, typically due to:
- Extended inactivity (no activity for 6+ months with no communicated reason)
- Conduct inconsistent with the `CODE_OF_CONDUCT.md`
- Their own request to step down

This is not punitive by default — inactivity removal is just housekeeping, and stepping down is always welcome. Former maintainers are credited in the project's history regardless.

## Adding a new package

Anyone can propose a new shared package via an issue. Maintainers evaluate proposals against:
- Is there a clear actuarial use case, and is it reusable beyond one person's specific context?
- Is someone (the proposer or another volunteer) committing to maintain it, at least initially?
- Does it duplicate an existing package or well-established external tool (in which case, contributing to that existing tool is usually better than fragmenting effort)?

Approval requires majority maintainer vote per the process above.

## "Reviewed" status for packages

A package may be marked "Reviewed" in the registry/README once it has: a test suite covering its core logic, documentation sufficient for a new user to get started, and sign-off from at least two maintainers who are not the primary author. This status is re-evaluated if the package goes unmaintained for an extended period.

## Amending this document

Changes to this governance document are themselves a non-routine decision (see above) — proposed via PR, decided by maintainer majority vote, with escalation to the committee available if needed.
