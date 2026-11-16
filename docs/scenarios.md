# Handover scenarios

These four scenarios describe how the proposed register should behave during a handover. They are fictional. Each one is built from one of the five simulated survey profiles, not from a real association, and none of them describes an event that has been observed. The tests use made-up service records and check proposed behaviour. There is no software yet, so none of these tests has been run.

Each scenario S1 to S4 is linked to one requirement, R1 to R4. The fifth profile is described at the end as an open question, not as a scenario.

## S1: website and mailbox (R1)

| Item | Description |
|---|---|
| Actor | Deputy for the association's website and shared mailbox |
| Trigger | The volunteer who managed the domain and the mailbox leaves. |
| Precondition | The register lists the website and the mailbox as services. For each one it holds the responsible role, the deputy, a review date and, where the association knows it, the provider's public recovery procedure. |
| Action | The deputy opens the service record to find out whom to contact and how recovery works at the provider. |
| Expected result | The deputy finds the organisational contact and the documented recovery route without seeing any credentials. If no route has been recorded, the record is clearly marked as incomplete. |
| Failure condition | A missing route looks complete. A password, recovery code or session link appears anywhere. The register suggests that it can recover the account itself. |
| Evidence status | Hypothetical. Built from simulated profile 1. Not tested. |

R1: For each critical service, the register records the organisational owner, a deputy, the provider's public recovery procedure and a review date. It shows clearly when the recovery route is missing. Recovery at the provider is out of scope.

## S2: social media and donations (R2)

| Item | Description |
|---|---|
| Actor | Volunteer coordinator responsible for the handover |
| Trigger | A volunteer who administered the social media accounts and the donation page steps down. Several people look after different services, and nobody knows whether the former administrator's access has been reviewed. |
| Precondition | The handover lists each service with two mandatory steps: a review of the outgoing person's access and a confirmation of the incoming role. |
| Action | The coordinator tries to close the handover. |
| Expected result | The handover cannot be closed while a mandatory step is open. When someone confirms a step, the register records who confirmed it and when. |
| Failure condition | The handover closes with a mandatory step still open. A confirmation is shown as proof that access changed at the provider. Payment or donor data is collected. |
| Evidence status | Hypothetical. Built from simulated profile 2. Not tested. |

R2: The review of outgoing access and the confirmation of the incoming role are separate mandatory steps for each service. A handover with an open mandatory step cannot be closed. A confirmation records what a person reports, not a verified change at the provider. No payment or donor data is collected.

## S3: shared archive (R3)

| Item | Description |
|---|---|
| Actor | Incoming treasurer |
| Trigger | The new treasurer takes office and needs to work with the association's shared archive. |
| Precondition | The register holds the archive's custodian role, a deputy and a reference to where the general filing guide is kept. The reference is not a private sharing link. |
| Action | The treasurer looks up the archive and confirms receipt of the handover item. |
| Expected result | The treasurer knows whom to ask and where the filing guide is, and confirms receipt without uploading anything. |
| Failure condition | The register asks for, or accepts, budgets, member files or document contents. A private sharing link is stored. The register appears to index, back up or restore the archive. |
| Evidence status | Hypothetical. Built from simulated profile 3. Not tested. |

R3: The register records the custodian role, a deputy and a non-secret reference to the filing guide. It does not store, index, recover or back up the archive. Finding the right person is a different task from recovering lost files.

## S4: a handover that already works (R4)

| Item | Description |
|---|---|
| Actor | Research lead, working with the association's role holder and deputy |
| Trigger | An association whose handovers already work with a written guide takes part in the comparison. |
| Precondition | The association has a primary role holder, a deputy and a written guide that it uses. |
| Action | The same handover task is done first with the written guide and then with the proposed register. Completion and upkeep effort are recorded for both. |
| Expected result | If the guide is enough, this is recorded as a success without a new tool. |
| Failure condition | Software is recommended although the guide was enough. The 24-hour practice in this example is treated as a general deadline or as a requirement to revoke access automatically. |
| Evidence status | Hypothetical. Built from simulated profile 4. Not tested. This scenario is the baseline for the comparison. |

R4: The association's existing method is tried first. If it is enough, the result is recorded as no demonstrated need for new software, and adoption is not pushed. The 24-hour practice in this example is not a general requirement.

## Profile 5: an open question

Profile 5 describes an association with no recent handover and little information about the next one. It is not a fifth scenario and must not be counted as an observed failure, since nothing has gone wrong. It is kept as a reminder that some associations will have nothing to report yet.

## Export and import

Moving records into and out of the register is tested separately as an engineering requirement. It is not part of S4.

## Planning references

| Scenario | Requirement | Planning item |
|---|---|---|
| S1 | R1 | VS-03, VS-04 |
| S2 | R2 | VS-05 |
| S3 | R3 | VS-03 |
| S4 | R4 | VS-01, VS-05 |

VS identifiers are planning references. They are not GitHub issue numbers.

[Back to README](../README.md)
