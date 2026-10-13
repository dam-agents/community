# Mission

`dam-agents` builds **DAM**, the open platform for running AI agents — any harness, any model, on Kubernetes — and the community around it.

This document states why the project exists, who it serves, and the principles we hold ourselves to.
It is the reference the rest of our community documents point back to.

## Why we exist

Every team running AI agents ends up rebuilding the same infrastructure: isolation, credential handling, orchestration, cost visibility.
That work is hard to get right, easy to get wrong, and dangerous when it is wrong — an agent runs code and makes network requests on its own.

DAM exists so that teams do not each have to solve this alone.
We provide the platform as open source, developed in the open, so the hard parts are built once, reviewed by many, and owned by the community that depends on them.

## Who we serve

- **Teams running agents in production**, who need isolation, credential safety, and cost controls they can audit.
- **Researchers and experimenters**, who need to run harnesses and models side by side with persistent, shareable environments.
- **Contributors**, who want to improve a platform they use and have their work reviewed and merged in the open.
- **Operators**, who deploy DAM on their own clusters and need the design documented, not inferred.

## Principles

- **Open by default.**
  Issues, pull requests, roadmap decisions, and development happen in public repositories.
  We reach each other in the open rather than by private channel, so an answer helps the next person too.

- **Security is a property of the infrastructure, not of good behaviour.**
  We assume an agent is untrusted and build real walls around it.
  We never ship a control that depends on the agent choosing to behave.

- **Explain the why.**
  Our documentation says not just what the system does but why it is built that way, so operators and contributors can reason about it.

- **Teams, not heroes.**
  The platform is built for teams to share, and the project is maintained by a group, with decisions and roster recorded in the open.

- **Respect the people, not just the code.**
  We hold ourselves to the norms in [`BEST_PRACTICES.md`](BEST_PRACTICES.md).

## How this connects to the rest of our docs

- [`README.md`](README.md) is the front door: what the org is and where everything lives.
- [`GOVERNANCE.md`](GOVERNANCE.md) records who maintains the project and how decisions are made.
- [`SECURITY.md`](SECURITY.md) is how to report a vulnerability.
- [`COMPLAINTS.md`](COMPLAINTS.md) is how to raise a concern and have it tracked to resolution.
- [`BEST_PRACTICES.md`](BEST_PRACTICES.md) collects our guidance for engaging with the project well.
