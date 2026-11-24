# Decisions

This page lists the decisions the project has made, the ones that are only proposed and the questions that are still open. A decision that is replaced stays in the list. It is marked as superseded and points to the decision that replaced it.

## Decision register

| ID | Decision | Status | Date | Details |
|---|---|---|---|---|
| DEC-01 | The project is called VereinsStaffel. | Accepted | 1 October 2026 | [Research log](../research-log.md) |
| DEC-02 | The register never stores reusable secrets for services, such as passwords, recovery codes, tokens or private keys. | Accepted | Not recorded | [Architecture](../architecture.md) |
| DEC-03 | Contacting associations stays with the founder. | Accepted | 30 September 2026 | [Research log](../research-log.md) |
| DEC-04 | Original application code would be licensed under AGPL-3.0-or-later. | Proposed | Not recorded | [Licensing](../licensing.md) |
| DEC-05 | Original documentation would be licensed under CC BY 4.0. | Proposed | Not recorded | [Licensing](../licensing.md) |
| DEC-06 | The register is a single self-hosted workspace for one association. | Proposed | Not recorded | [Architecture](../architecture.md) |
| DEC-07 | Development follows the six-month sequence in the roadmap. | Proposed | Not recorded | [Roadmap](../roadmap.md) |
| DEC-08 | Continue the project after the first survey round, and compare the register with a written guide in the next round. | Accepted | 23 November 2026 | [DEC-08 in detail](#dec-08-in-detail) |
| DEC-09 | Pages for associations and volunteers have a German section first and an English section after it. Technical pages stay in English. | Accepted | 24 November 2026 | [DEC-09 in detail](#dec-09-in-detail) |

## DEC-08 in detail

Decided by the founder on 23 November 2026.

The evidence is the first survey round: seven responses from members of four associations. Five responses report a handover with problems that are still open, and five report an account that could not be reached for a while. Four respondents would consider using a tool of this kind and three would want to see it first. Three associations have agreed in writing to support the project. The limits of this evidence are described in [Research and evidence](../research/README.md).

The alternatives were to narrow the scope to email, domain and recovery details only, or to wait for more responses before deciding. Narrowing was not chosen because the problems reported also involve shared files and former office holders' access. Waiting was not chosen because the results already pass the planned threshold in most respects, and the remaining gaps can be closed in the next round.

The next round asks for an association code so that each association is counted once, and runs the comparison with a written guide described in scenario S4. If the guide turns out to be enough, that result will be recorded as a new decision.

## DEC-09 in detail

Decided by the founder on 24 November 2026.

The project is meant for volunteers in associations in Germany, and not all of them read English. Until now every page was in English only.

The pages with a German section are the README, the privacy page, the handover scenarios, the research summary and the code of conduct. The other pages stay in English. Commit messages stay in English. The rule for contributors is in [Contributing](../../CONTRIBUTING.md).

The alternatives were to keep English only, to translate every page, or to keep German in separate files. English only was not chosen because the pages that volunteers read would stay hard to follow for some of them. Translating every page was not chosen because a single maintainer would have to keep two versions of the technical pages up to date. Separate files were not chosen because they are easier to miss and can drift apart from the English version.

## Open questions

- Do the problems from the first survey round hold up when more associations are asked and each is counted once? See [Research and evidence](../research/README.md).
- Is software needed at all, or is a written guide enough?
- Who has the time to run and maintain the project?

## Recording a new decision

Each new entry gives:

- the date
- who decided
- the evidence it is based on
- the alternatives that were considered
- the decision itself
- the earlier decision it replaces, if any

[Back to README](../../README.md)
