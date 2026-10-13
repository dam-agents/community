# Security policy

DAM is infrastructure for running untrusted AI agents safely.
Security is the property we take most seriously, so we want vulnerability reports and we commit to handling them well.

This policy covers every repository in the `dam-agents` organization.

## Reporting a vulnerability

**Report privately. Do not open a public issue, pull request, or discussion for a suspected vulnerability**, and do not describe it in a public channel until it has been resolved and disclosed.

Report through **GitHub private security advisories**, which keep the report visible only to you and the maintainers until a fix is ready:

1. Go to the affected repository's **Security** tab — for the platform, [`dam-agents/dam` → Security](https://github.com/dam-agents/dam/security/advisories).
2. Choose **Report a vulnerability**.
3. Describe the issue (see below). GitHub creates a private advisory and notifies the maintainers.

If you cannot use GitHub advisories, open a minimal public issue that says only *"requesting a private security contact"* — with **no details** — and a maintainer will open a private channel with you.

### What to include

The more of this you can provide, the faster we can act:

- The affected repository, component, and version or commit.
- What the vulnerability lets an attacker do, and who is affected.
- Steps to reproduce, or a proof of concept.
- Any suggested remediation.

Please describe the **class** of problem and how to reproduce it, rather than publishing a weaponized exploit.

## What to expect

We handle reports in stages, and we will keep you updated as each one completes:

| Stage | What happens | Target |
| --- | --- | --- |
| **Acknowledgement** | A maintainer confirms we received the report. | Within 3 business days. |
| **Triage** | We assess severity and impact and tell you whether we have accepted it as a vulnerability. | Within 10 business days. |
| **Fix** | We develop and test a fix, privately, in coordination with you where it helps. | Depends on severity and complexity. |
| **Disclosure** | We publish an advisory crediting you (unless you prefer to remain anonymous) and release the fix. | Coordinated with you. |

These are targets, not guarantees, but they are what we hold ourselves to and what the escalation path below exists to protect.

## Coordinated disclosure

We follow coordinated disclosure.
We ask that you give us a reasonable chance to release a fix before any public disclosure — typically up to 90 days from acknowledgement, shorter for issues already being exploited.
We will work with you on timing, and we credit reporters in the advisory by default.

## Scope

**In scope:** code and configuration in the `dam-agents` organization's repositories, and the security properties DAM claims — agent isolation, credential isolation, network controls, and human-approval gates.
The platform's security model is documented in the dam repository:

- [Security overview](https://github.com/dam-agents/dam/blob/main/docs/strategy/security-overview.md)
- [Security model](https://github.com/dam-agents/dam/blob/main/docs/strategy/security-model.md)
- [Supply-chain security](https://github.com/dam-agents/dam/blob/main/docs/security/supply-chain.md)

**Out of scope:** the hosted deployment operated by IBM Research (report those through IBM's own channels), third-party services DAM integrates with, and findings that require a privilege level the threat model already grants.

## How we keep the project secure

Beyond handling reports, the maintainers commit to the following:

- **Scanning.** Repositories are scanned for vulnerabilities in dependencies and code, and Critical and High findings are fixed rather than left open.
- **Notifications.** A named maintainer reviews vulnerability notifications for the project's dependencies at least weekly.
- **Spot-checks.** The maintainers spot-check the organization's repositories at least quarterly for exposed secrets, overly broad permissions, and stale access, and fix what they find.
- **Incidents.** An actual or suspected compromise of a system the project operates, such as unauthorized access or loss of data integrity, is reported immediately to IBM's Cyber Security Incident Response Team (CSIRT), and the maintainers follow the incident manager's direction.
  Affected users are told through a published advisory once it is safe to do so.

## Escalation path

If a report stalls — no acknowledgement within the target window, or triage that goes quiet — escalate so it reaches someone:

1. **Comment on the advisory** asking for a status update. All maintainers are notified.
2. **Open a public issue** in [`dam-agents/community`](https://github.com/dam-agents/community/issues) titled *"security report awaiting response"*, with **no vulnerability details** — just that a private report has not been acknowledged.
   This puts the delay in front of the whole maintainer group in the open.
3. If it remains unresolved, follow the general [complaint and escalation policy](COMPLAINTS.md), which routes an unresolved concern to the maintainers as a group.

The [maintainers](GOVERNANCE.md#maintainers) are collectively responsible for security response; the escalation path exists so a single unavailable person never blocks a report.
