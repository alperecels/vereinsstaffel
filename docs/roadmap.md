# Roadmap

This is a proposed plan for six months of development. The months are counted from the start of a funded project. There are no calendar dates because there is no funding decision and no start date. Everything below is intended work, not work that has been done.

The current phase, writing documentation before a funding decision, is separate from this plan. No software is being built at the moment.

## Proposed scope

The first prototype would support one association workspace with:

- accounts created by an administrator
- services, people and roles
- handovers and the tasks each handover requires
- gaps, such as a service without a deputy or without a known recovery route
- a history of changes (audit log)
- exports that can be moved to another installation

The interface is proposed in German and English. The language of the research questionnaire is a separate choice.

## Not included

- a password vault or any other store for credentials
- integrations with providers
- automatic takeover of accounts
- security scanning or compliance scores
- live incident response
- several organisations on one installation, or billing
- single sign-on
- a mobile app

When the register shows a gap, it means a responsibility or a handover step is missing. It does not report security vulnerabilities.

## Six proposed months

Each month builds on the one before. Development after month 1 starts only if the scope decision at the end of month 1 is to go ahead. VS identifiers are planning references, not GitHub issue numbers.

### Month 1: research and baseline (VS-01, VS-02)

Reconcile the six-question and nine-item questionnaires, collect real responses and compare them with handovers done using a written guide. Review the proposed scope and the threat model. Set up a fresh local installation and check that workspaces are kept apart, using fictional records only.

Evidence at the end: the anonymous summary of responses (R02 in [Research and evidence](research/README.md)), the comparison with the written guide, and a recorded decision to go ahead, narrow the scope or stop.

### Month 2: service ownership (VS-03, VS-04)

Using fictional records, show that each service can have a responsible role and a deputy, that public recovery references can be stored safely (S1) and that an archive custodian can be recorded (S3).

Evidence at the end: missing information is visible without storing any files, and test values that the register rejects, such as text that looks like a password, never appear in its output.

### Month 3: handover (VS-05)

Build the mandatory handover steps, the access review confirmation and closing a handover by an authorised person (S2). Compare the same handover done with the association's written guide (S4).

Evidence at the end: tests for both refused and successful closing, and the result of the comparison, including the case where the guide is enough.

### Month 4: moving data (VS-06)

Test versioned export in JSON and CSV, a preview before import and rollback after a failed import. This is an engineering test and is separate from scenario S4.

Evidence at the end: an export followed by an import gives the same records, and rollback works.

### Month 5: hardening (VS-07)

Test use with a keyboard only, German and English labels, permissions, removal of sensitive values from logs, and restoring from a backup.

Evidence at the end: a test result for each of these.

### Month 6: pilot preparation (VS-08)

Write release notes and an installation guide, and prepare a demo with fictional data. Ask a willing outside operator to install the register without help from the developers and to report any problems.

Evidence at the end: the guide, the demo, and either the operator's report or a clear statement that no independent trial has taken place.

## Not assumed

This plan does not assume funding, pilot partners or start dates. The capacity and budget for each month have not been settled.

The scenarios S1 to S4 are described in [Handover scenarios](scenarios.md).

[Back to README](../README.md)
