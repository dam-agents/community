# Governance

This document records who maintains the `dam-agents` project and how decisions are made.
It is the reference that the [security](SECURITY.md) and [complaint](COMPLAINTS.md) escalation paths point to.

## Principles

The project is maintained by a **group**, not an individual.
Decisions are made in the open and recorded, so the reasoning is available to the next person and no single person is a single point of failure or a sole judge of a dispute.

## Maintainers

Maintainers triage issues, review pull requests, and make merge and release decisions.
They are collectively responsible for security response, complaint handling, and Code of Conduct enforcement.

This is the **canonical roster** for every repository in the `dam-agents` organization, including the platform repository [`dam-agents/dam`](https://github.com/dam-agents/dam).
Changes to the roster are made by pull request to this file.

Names are listed alphabetically by last name; the order carries no meaning.

| Name | GitHub |
| --- | --- |
| Petr Bulánek | [@PetrBulanek](https://github.com/PetrBulanek) |
| Tomáš Dvořák | [@Tomas2D](https://github.com/Tomas2D) |
| Matous Havlena | [@matoushavlena](https://github.com/matoushavlena) |
| Lukáš Janeček | [@xjacka](https://github.com/xjacka) |
| Jan Jeliga | [@jjeliga](https://github.com/jjeliga) |
| Radek Ježek | [@jezekra1](https://github.com/jezekra1) |
| Petr Kadlec | [@kapetr](https://github.com/kapetr) |
| Tomas Pilar | [@pilartomas](https://github.com/pilartomas) |
| Jan Pokorný | [@JanPokorny](https://github.com/JanPokorny) |
| Tomáš Weiss | [@tomkis](https://github.com/tomkis) |
| Jenna Winkler | [@jenna-winkler](https://github.com/jenna-winkler) |

## How decisions are made

- **Routine changes** — bug fixes, documentation, and small improvements — are decided by normal review: a maintainer approves and merges a pull request.
- **Significant changes** — anything that changes the platform's design or behaviour in a meaningful way — start as an issue or discussion so the approach can be agreed before the work.
  The platform repository records architectural decisions; see its [`docs/`](https://github.com/dam-agents/dam/tree/main/docs).
- **Disagreements** are resolved in the open.
  Maintainers aim for consensus; where consensus cannot be reached, the maintainer group decides as a group, and the decision and its reasoning are recorded.

## Escalation and conflict of interest

The escalation paths in [`SECURITY.md`](SECURITY.md) and [`COMPLAINTS.md`](COMPLAINTS.md) route an unresolved matter to the maintainer group rather than to a single person.
When a matter concerns a specific maintainer, that maintainer recuses themselves from reviewing it.

## Organization administration

The `dam-agents` organization is sponsored by IBM and administered by active IBM employees.

- **Ownership.** Organization owners are responsible for maintaining the organization's settings, permissions, and repositories.
  The organization always has at least one active IBM employee as an owner.
- **Onboarding.** A new member or maintainer is proposed by an existing maintainer in a pull request to the roster above, approved by the maintainer group, and then given the least access their role needs.
- **Offboarding.** When someone leaves the project or their role ends, their access is removed and the roster is updated by pull request, promptly and no later than their last day where that is known.
  Access is reviewed at least quarterly to catch anyone missed.
- **Watching.** At least one organization owner watches the organization's repositories, so new issues, pull requests, and security alerts reach them.
- **Spot-checks.** Repositories are spot-checked on the cadence set in [`SECURITY.md`](SECURITY.md#how-we-keep-the-project-secure).
- **Internal community.** For organizational questions, whether about community management or technical direction, the owners consult IBM's internal open source community early rather than late.

## If the project loses its IBM owners

If no active IBM employee remains to take responsibility for the organization, the maintainers act within 90 days to either:

1. **Hand off** ownership of the organization and its repositories to non-IBM maintainers who agree to this governance and the community policies, or
2. **Archive** the repositories so they remain readable but no longer accept changes, with a notice in each README saying so.

The decision and its reasoning are recorded in an issue in this repository.

## Changes to governance

Changes to this document, and to the community policies it governs, are made by pull request to this repository and reviewed by the maintainers like any other change.

## Getting in touch

Reach us in the open rather than by direct message, so the answer helps the next person too:

- **Bugs, features, and proposed changes:** [dam issues](https://github.com/dam-agents/dam/issues).
- **Questions and ideas:** [dam discussions](https://github.com/dam-agents/dam/discussions).
- **Community, governance, and complaints:** [community issues](https://github.com/dam-agents/community/issues).
