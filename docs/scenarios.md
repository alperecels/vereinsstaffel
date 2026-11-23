# Handover scenarios

The four scenarios below describe how the proposed register should behave during a handover. Each one was first built from one of five simulated survey profiles. The first survey round has since reported real problems that match S1 to S3; the details are in [Research and evidence](research/README.md). There is no software yet, so none of the tests has been run.

S1 to S4 each lead to one requirement, R1 to R4.

## S1: website and mailbox

| Field | Content |
|---|---|
| Actor | Deputy for the website and the shared mailbox |
| Trigger | The volunteer who managed the domain and the mailbox leaves. |
| Precondition | Both services are in the register with a responsible role, a deputy, a review date and, if known, the provider's public recovery procedure. |
| Action | The deputy looks up whom to contact and how recovery works at the provider. |
| Expected result | The deputy finds the contact and the recovery route without seeing any credentials. A missing route is marked as incomplete. |
| Failure condition | A missing route looks complete, or a password, recovery code or session link is shown. |
| Requirement | R1: record the owner, deputy, recovery procedure and review date for each critical service. Recovery itself stays with the provider. |
| Evidence status | Built from simulated profile 1. In the first survey round, 5 of 7 responses report an account that could not be reached for a while and 3 report out-of-date recovery details. One describes a domain registered to a former administrator's private email address. Not tested. |

## S2: social media and donations

| Field | Content |
|---|---|
| Actor | Volunteer coordinator in charge of the handover |
| Trigger | The volunteer who ran the social media accounts and the donation page steps down. Nobody knows whether their access has been reviewed. |
| Precondition | Each service in the handover has two mandatory steps: review the outgoing person's access and confirm the incoming role. |
| Action | The coordinator tries to close the handover. |
| Expected result | Closing is refused while a mandatory step is open. Each confirmation is stored with a name and a date. |
| Failure condition | The handover closes with an open step, or a confirmation is presented as proof of a change at the provider. |
| Requirement | R2: the two steps are separate and both are mandatory. A confirmation records what someone reports. No payment or donor data is collected. |
| Evidence status | Built from simulated profile 2. In the first survey round, 1 of 7 responses reports a former office holder who kept access and 2 report that nobody knew who managed an account. Not tested. |

## S3: shared archive

| Field | Content |
|---|---|
| Actor | Incoming treasurer |
| Trigger | The new treasurer needs to work with the shared archive. |
| Precondition | The register names the archive's custodian role and deputy, and says where the filing guide is kept. This is a plain description, not a sharing link. |
| Action | The treasurer looks up the archive and confirms receipt. |
| Expected result | The treasurer knows whom to ask and confirms receipt without uploading anything. |
| Failure condition | The register accepts file contents or stores a private sharing link. |
| Requirement | R3: record who looks after the archive, not the archive itself. Finding the right person is a different job from recovering lost files. |
| Evidence status | Built from simulated profile 3. In the first survey round, 2 of 7 responses report a file that could not be found. One describes budget and member lists that were gone after the treasurer left. Not tested. |

## S4: a handover that already works

| Field | Content |
|---|---|
| Actor | Research lead, with the association's role holder and deputy |
| Trigger | An association whose handovers already work with a written guide joins the comparison. |
| Precondition | The association has a role holder, a deputy and a guide it actually uses. |
| Action | The same task is done with the guide first, then with the register. Completion and upkeep effort are noted for both. |
| Expected result | If the guide is enough, that counts as a success without new software. |
| Failure condition | Software is recommended anyway, or the example's 24-hour practice is treated as a rule for every association. |
| Requirement | R4: test the existing method first and accept it when it works. |
| Evidence status | Built from simulated profile 4. In the first survey round, 1 of 7 responses reports a handover without problems and 1 has written handover instructions. Nobody said their current method was enough. Not tested. This is the baseline for the comparison. |

## Profile 5

Profile 5 is an association with no recent handover and little known about the next one. Nothing has gone wrong there, so it counts neither as a failure nor as a fifth scenario. In the first survey round, 1 of 7 responses reports no handover in the last 24 months.

## Export and import

Moving records into and out of the register is tested on its own. It is not part of S4.

## Planning references

| Scenario | Requirement | Planning item |
|---|---|---|
| S1 | R1 | VS-03, VS-04 |
| S2 | R2 | VS-05 |
| S3 | R3 | VS-03 |
| S4 | R4 | VS-01, VS-05 |

VS identifiers are planning references, not GitHub issue numbers.

[Back to README](../README.md)
