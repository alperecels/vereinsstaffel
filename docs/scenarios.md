# Übergabeszenarien | Handover scenarios

[Deutsch](#deutsch) | [English](#english)

## Deutsch

Die vier Szenarien beschreiben, wie sich das vorgeschlagene Register bei einer Übergabe verhalten soll. Jedes wurde zunächst aus einem von fünf simulierten Befragungsprofilen entwickelt. Die erste Befragungsrunde hat inzwischen echte Probleme ergeben, die zu S1 bis S3 passen; die Einzelheiten stehen unter [Forschung und Belege](research/README.md). Software gibt es noch nicht, deshalb wurde keiner der Tests durchgeführt.

S1 bis S4 führen jeweils zu einer Anforderung, R1 bis R4.

### S1: Website und Postfach

| Feld | Inhalt |
|---|---|
| Beteiligte Person | Stellvertretung für die Website und das gemeinsame Postfach |
| Auslöser | Die ehrenamtliche Person, die Domain und Postfach verwaltet hat, hört auf. |
| Voraussetzung | Beide Dienste stehen im Register, mit zuständiger Rolle, Stellvertretung, Prüfdatum und, falls bekannt, dem öffentlichen Wiederherstellungsverfahren des Anbieters. |
| Handlung | Die Stellvertretung schlägt nach, an wen sie sich wenden muss und wie die Wiederherstellung beim Anbieter abläuft. |
| Erwartetes Ergebnis | Die Stellvertretung findet die Ansprechperson und den Wiederherstellungsweg, ohne Zugangsdaten zu sehen. Ein fehlender Weg wird als unvollständig markiert. |
| Fehlerfall | Ein fehlender Weg wirkt vollständig, oder ein Passwort, ein Wiederherstellungscode oder ein Sitzungslink wird angezeigt. |
| Anforderung | R1: Für jeden wichtigen Dienst werden Zuständigkeit, Stellvertretung, Wiederherstellungsverfahren und Prüfdatum festgehalten. Die Wiederherstellung selbst bleibt beim Anbieter. |
| Stand der Belege | Aus dem simulierten Profil 1 entwickelt. In der ersten Befragungsrunde berichten 5 von 7 Antworten, dass ein Konto eine Zeit lang nicht erreichbar war, und 3 von veralteten Wiederherstellungsdaten. Eine Antwort beschreibt eine Domain, die mit den persönlichen Kontaktdaten einer früheren ehrenamtlichen Person registriert war. Nicht getestet. |

### S2: Social Media und Spenden

| Feld | Inhalt |
|---|---|
| Beteiligte Person | Person, die Ehrenamtliche koordiniert und die Übergabe verantwortet |
| Auslöser | Die ehrenamtliche Person, die die Social-Media-Konten und die Spendenseite betreut hat, tritt zurück. Niemand weiß, ob ihr Zugang überprüft wurde. |
| Voraussetzung | Für jeden Dienst der Übergabe gibt es zwei Pflichtschritte: den Zugang der ausscheidenden Person prüfen und die übernehmende Rolle bestätigen. |
| Handlung | Die koordinierende Person versucht, die Übergabe abzuschließen. |
| Erwartetes Ergebnis | Der Abschluss wird verweigert, solange ein Pflichtschritt offen ist. Jede Bestätigung wird mit Name und Datum gespeichert. |
| Fehlerfall | Die Übergabe wird mit einem offenen Schritt abgeschlossen, oder eine Bestätigung wird als Nachweis einer Änderung beim Anbieter dargestellt. |
| Anforderung | R2: Die beiden Schritte sind getrennt und beide verpflichtend. Eine Bestätigung hält fest, was jemand meldet. Zahlungs- oder Spendendaten werden nicht erfasst. |
| Stand der Belege | Aus dem simulierten Profil 2 entwickelt. In der ersten Befragungsrunde berichtet 1 von 7 Antworten von einer Person, die früher ein Vereinsamt hatte und ihren Zugang behalten hat, und 2 davon, dass niemand wusste, wer ein Konto verwaltet. Nicht getestet. |

### S3: Gemeinsames Archiv

| Feld | Inhalt |
|---|---|
| Beteiligte Person | Neue Kassenführung |
| Auslöser | Die neue Kassenführung muss mit dem gemeinsamen Archiv arbeiten. |
| Voraussetzung | Das Register nennt die für das Archiv zuständige Rolle und die Stellvertretung und gibt an, wo die Ablageanleitung liegt. Das ist eine einfache Beschreibung, kein Freigabelink. |
| Handlung | Die neue Kassenführung schlägt das Archiv nach und bestätigt den Empfang. |
| Erwartetes Ergebnis | Die neue Kassenführung weiß, wen sie fragen kann, und bestätigt den Empfang, ohne etwas hochzuladen. |
| Fehlerfall | Das Register nimmt Dateiinhalte an oder speichert einen privaten Freigabelink. |
| Anforderung | R3: Festgehalten wird, wer sich um das Archiv kümmert, nicht das Archiv selbst. Die richtige Person zu finden ist eine andere Aufgabe, als verlorene Dateien wiederherzustellen. |
| Stand der Belege | Aus dem simulierten Profil 3 entwickelt. In der ersten Befragungsrunde berichten 2 von 7 Antworten, dass eine Datei nicht gefunden wurde. Eine Antwort beschreibt ältere Dateien, die nicht mehr auffindbar waren, nachdem eine Person ihr Vereinsamt abgegeben hatte. Nicht getestet. |

### S4: Eine Übergabe, die schon funktioniert

| Feld | Inhalt |
|---|---|
| Beteiligte Person | Forschungsleitung, gemeinsam mit der zuständigen Person und der Stellvertretung im Verein |
| Auslöser | Ein Verein, dessen Übergaben mit einer schriftlichen Anleitung bereits funktionieren, nimmt am Vergleich teil. |
| Voraussetzung | Der Verein hat eine zuständige Person, eine Stellvertretung und eine Anleitung, die er tatsächlich nutzt. |
| Handlung | Dieselbe Aufgabe wird zuerst mit der Anleitung und dann mit dem Register erledigt. Für beide werden Abschluss und Pflegeaufwand notiert. |
| Erwartetes Ergebnis | Wenn die Anleitung genügt, gilt das als Erfolg ohne neue Software. |
| Fehlerfall | Software wird trotzdem empfohlen, oder die 24-Stunden-Praxis aus dem Beispiel wird als Regel für alle Vereine behandelt. |
| Anforderung | R4: Die vorhandene Methode wird zuerst getestet und angenommen, wenn sie funktioniert. |
| Stand der Belege | Aus dem simulierten Profil 4 entwickelt. In der ersten Befragungsrunde berichtet 1 von 7 Antworten von einer Übergabe ohne Probleme, und 1 Antwort nennt schriftliche Übergabeanweisungen. Niemand gab an, dass die bisherige Methode ausreicht. Nicht getestet. Dies ist die Grundlage für den Vergleich. |

### Profil 5

Profil 5 ist ein Verein ohne kürzliche Übergabe, der wenig über die nächste weiß. Dort ist nichts schiefgegangen, deshalb zählt es weder als Fehlschlag noch als fünftes Szenario. In der ersten Befragungsrunde berichtet 1 von 7 Antworten, dass es in den letzten 24 Monaten keine Übergabe gab.

### Export und Import

Das Übertragen von Einträgen in das Register und aus ihm heraus wird für sich getestet. Es gehört nicht zu S4.

### Planungsbezüge

| Szenario | Anforderung | Arbeitspaket |
|---|---|---|
| S1 | R1 | VS-03, VS-04 |
| S2 | R2 | VS-05 |
| S3 | R3 | VS-03 |
| S4 | R4 | VS-01, VS-05 |

VS-Kennungen sind Planungsbezüge, keine GitHub-Issue-Nummern.

## English

The four scenarios below describe how the proposed register should behave during a handover. Each one was first built from one of five simulated survey profiles. The first survey round has since reported real problems that match S1 to S3; the details are in [Research and evidence](research/README.md). There is no software yet, so none of the tests has been run.

S1 to S4 each lead to one requirement, R1 to R4.

### S1: website and mailbox

| Field | Content |
|---|---|
| Actor | Deputy for the website and the shared mailbox |
| Trigger | The volunteer who managed the domain and the mailbox leaves. |
| Precondition | Both services are in the register with a responsible role, a deputy, a review date and, if known, the provider's public recovery procedure. |
| Action | The deputy looks up whom to contact and how recovery works at the provider. |
| Expected result | The deputy finds the contact and the recovery route without seeing any credentials. A missing route is marked as incomplete. |
| Failure condition | A missing route looks complete, or a password, recovery code or session link is shown. |
| Requirement | R1: record the owner, deputy, recovery procedure and review date for each critical service. Recovery itself stays with the provider. |
| Evidence status | Built from simulated profile 1. In the first survey round, 5 of 7 responses report an account that could not be reached for a while and 3 report out-of-date recovery details. One describes a domain registered with a former volunteer's personal contact details. Not tested. |

### S2: social media and donations

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

### S3: shared archive

| Field | Content |
|---|---|
| Actor | Incoming treasurer |
| Trigger | The new treasurer needs to work with the shared archive. |
| Precondition | The register names the archive's custodian role and deputy, and says where the filing guide is kept. This is a plain description, not a sharing link. |
| Action | The treasurer looks up the archive and confirms receipt. |
| Expected result | The treasurer knows whom to ask and confirms receipt without uploading anything. |
| Failure condition | The register accepts file contents or stores a private sharing link. |
| Requirement | R3: record who looks after the archive, not the archive itself. Finding the right person is a different job from recovering lost files. |
| Evidence status | Built from simulated profile 3. In the first survey round, 2 of 7 responses report a file that could not be found. One describes older files that could no longer be found after an office holder left. Not tested. |

### S4: a handover that already works

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

### Profile 5

Profile 5 is an association with no recent handover and little known about the next one. Nothing has gone wrong there, so it counts neither as a failure nor as a fifth scenario. In the first survey round, 1 of 7 responses reports no handover in the last 24 months.

### Export and import

Moving records into and out of the register is tested on its own. It is not part of S4.

### Planning references

| Scenario | Requirement | Planning item |
|---|---|---|
| S1 | R1 | VS-03, VS-04 |
| S2 | R2 | VS-05 |
| S3 | R3 | VS-03 |
| S4 | R4 | VS-01, VS-05 |

VS identifiers are planning references, not GitHub issue numbers.

[Back to README](../README.md)
