# Best practices

How to engage with the `dam-agents` project and community well.
This is the guidance referenced by the [mission](MISSION.md); it covers both participating in the community and working with the organization.

## How we work: in the open

Issues, pull requests, and roadmap discussion all happen in public.
Reach us in the open rather than by direct message, so the answer helps the next person too.

| Channel | Use it for |
| --- | --- |
| [dam issues](https://github.com/dam-agents/dam/issues) | Bugs, feature requests, and proposed changes to the platform. |
| [dam discussions](https://github.com/dam-agents/dam/discussions) | Questions, ideas, and roadmap conversation. |
| [community issues](https://github.com/dam-agents/community/issues) | Governance questions and concerns about the community itself. |

## Engaging with the organization

- **Search first.** Before opening an issue or question, check whether it already exists.
- **Read the architecture before proposing changes.** The platform's design is documented in [`dam-agents/dam/docs`](https://github.com/dam-agents/dam/tree/main/docs); it is the source of truth, so don't infer the design from the code alone.
- **Agree on the approach before large work.** For anything bigger than a small fix, open or comment on an issue first so maintainers can agree on the approach and avoid duplicated effort.
- **Follow each repository's contributing guide.** Code specifics — setup, checks, commit and sign-off rules — live in each repo's own guide, for example [`dam-agents/dam/CONTRIBUTING.md`](https://github.com/dam-agents/dam/blob/main/CONTRIBUTING.md).
- **Keep changes focused.** One logical change per pull request is easier to review and merge.

## Writing a good issue

- State what you expected, what happened, and how to reproduce it.
- Include versions and environment where relevant.
- Describe behaviour and decisions rather than attacking a person.
- Don't put secrets, credentials, or private data in a public issue.

If you use a coding agent, the `dam` repository ships issue-writing skills that work with any agent harness, such as Claude Code, Codex, or Pi:

- [`draft-issue`](https://github.com/dam-agents/dam/blob/main/.agents/skills/draft-issue/SKILL.md) holds the templates and writing guidelines for each issue type (epic, feature, task, bug, or research task).
- [`file-issue`](https://github.com/dam-agents/dam/blob/main/.agents/skills/file-issue/SKILL.md) drafts an issue, gets your approval, and files it with the `gh` CLI.

The written rules are in [`issue-guidelines.md`](https://github.com/dam-agents/dam/blob/main/docs/guidelines/issue-guidelines.md).

## Participating in the community

- Be respectful and assume good faith.
- Keep discussion on the record and on topic.
- Help the next person: a clear question and a clear answer are a contribution.

## Reporting problems

- **Security vulnerabilities** go through [`SECURITY.md`](SECURITY.md) — report them privately, never in a public issue.
- **Complaints and unresolved concerns** go through [`COMPLAINTS.md`](COMPLAINTS.md), which states how they are monitored and escalated.
