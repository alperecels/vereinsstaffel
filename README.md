# VereinsStaffel

When a volunteer steps down from running an association's website, the board usually knows who is leaving. The person taking over still needs three answers: who is responsible for the task now, who can step in, and what is left to do.

VereinsStaffel is a proposed self-hosted register for small volunteer-run associations in Germany. It would record a responsible role, a deputy and a review date for each digital service, and keep track of the open steps in a handover. It would not store passwords, recovery codes, tokens or private keys, and it would not change access rights at any external provider.

## Documentation

- [Research and evidence](docs/research/README.md): what evidence exists, what is missing and how the first research round is planned
- [Handover scenarios](docs/scenarios.md): four fictional handovers and the requirements they lead to
- [Roadmap](docs/roadmap.md): proposed scope and six months of development, with the evidence expected at the end of each month
- [Planning](docs/planning.md): proposed work items VS-01 to VS-08 with their dependencies and acceptance evidence
- [Architecture](docs/architecture.md): proposed design, what data the register may hold and what it must never store
- [Privacy and data protection](docs/privacy.md): how data is handled in this repository and in the research, and what an association would have to decide
- [Prior art and alternatives](docs/prior-art.md): existing tools and a written guide, and how they will be compared on the same handover task
- [Licensing](docs/licensing.md): proposed licences and the decisions still open
- [Research log](docs/research-log.md): dated record of what happened, what it means and which sources were used
- [Decisions](docs/decisions/README.md): accepted and proposed decisions, and the questions still open

## Who it is for

Board members, volunteer coordinators and people who look after digital services in small registered associations (eingetragene Vereine). We intend to include migrant-led associations and organisations that work with migrants in the first research round. Taking part depends on experience with handovers, not on citizenship or assumed technical skill.

## How it would work

A coordinator links a service, such as the website or the shared mailbox, to a responsible role and a deputy. During a handover, the incoming volunteer sees which steps are still open. When someone marks a step as done, the register records what the association reports. It cannot prove that a provider has actually changed permissions or restored access.

## Project status

This repository contains documentation only. There is no software yet.

We are preparing an application to the Prototype Fund and want to find out whether associations need software for this at all. The plan is to compare the same tasks done with an association's existing written guide and with the proposed register. If the written guide works, keeping it is a valid result.

The four handover scenarios in this project are illustrative. The five survey profiles used so far are simulated and are not responses from real associations. No field findings are claimed here.

## Taking part

Contributions are currently limited to the documentation. See the [contributing guide](CONTRIBUTING.md), the [code of conduct](CODE_OF_CONDUCT.md) and the [security policy](SECURITY.md).

## Licence

Not decided yet. The proposed licences and the open decisions are described in [Licensing](docs/licensing.md). A licence will be added once the rights holders have approved it.
