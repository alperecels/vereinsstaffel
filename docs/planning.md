# Planning

This page lists the proposed work for the six months of development described in the [roadmap](roadmap.md). It is future work. It can only start after a funding decision and a decision on scope.

VS identifiers are planning references, not GitHub issue numbers. When an issue is opened for an item, its link is added here. Nobody is assigned yet. The roles below are proposals, and no one's capacity has been agreed.

## Milestones

| Milestone | Items |
|---|---|
| Month 1: research and baseline | VS-01, VS-02 |
| Month 2: service ownership | VS-03, VS-04 |
| Month 3: handover | VS-05 |
| Month 4: moving data | VS-06 |
| Month 5: hardening | VS-07 |
| Month 6: pilot preparation | VS-08 |

Each milestone ends with evidence a reviewer can check.

## Items

### VS-01: Compare real handovers with the checklist baseline

Proposed role: research lead. Anonymise the evidence from real handovers and compare it with the written checklist. Depends on: the start of the project. Done when: a decision to go ahead, narrow the scope or stop is recorded together with the evidence behind it. GitHub issue: not opened yet.

### VS-02: Threat model, scope and foundation

Proposed role: technical lead. Record the threat model and the agreed scope, then set up the foundation. Depends on: VS-01. Done when: a fresh local installation works and workspaces are kept apart, shown with fictional records. GitHub issue: not opened yet.

### VS-03: Service owners, deputies and archive custodians

Proposed role: domain contributor. Model who owns each critical service, who deputises and who looks after the archive ([S1 and S3](scenarios.md)). Depends on: VS-02. Done when: missing information is visible without any files being stored. GitHub issue: not opened yet.

### VS-04: Safe input for recovery routes

Proposed role: reviewer. Check that recovery routes can be entered safely. Depends on: VS-02. Done when: test values that the register rejects never appear in its output. GitHub issue: not opened yet.

### VS-05: Handover closure and comparison

Proposed role: workflow contributor. Build the handover steps for [S2](scenarios.md) and compare the same transfer done with a written guide (S4). Depends on: VS-03 and VS-04. Done when: closing a handover has been tested for both refusal and success, and the comparison is recorded. GitHub issue: not opened yet.

### VS-06: Export and import

Proposed role: data contributor. Test the export and import preview, rollback and a full round trip. This is an engineering requirement and is separate from S4. Depends on: VS-05. Done when: an export followed by an import gives the same records, and rollback works. GitHub issue: not opened yet.

### VS-07: Accessibility and safety checks

Proposed role: reviewer. Show keyboard navigation, removal of sensitive values, safe export, restoring from a backup and coverage of both interface languages. Depends on: VS-06. Done when: each of these has a recorded result. GitHub issue: not opened yet.

### VS-08: Installation guide and pilot report

Proposed role: maintainer. Document installation and upgrades. Record a pilot operator's experience, or state clearly that no independent trial has taken place. Depends on: VS-07. Done when: the guide and the report or statement exist, and unresolved material issues have been reviewed before any release. GitHub issue: not opened yet.

## Issue format

Labels: research, decision, implementation, verification and blocked.

Each issue states the user need, a bounded output, its dependencies, an acceptance test and a link to the evidence. Real association records are never attached to an issue. People are assigned only after their capacity has been agreed.

[Back to README](../README.md)
