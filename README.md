# Cyber Security

## Was ist Cyber-Security

- befasst sich mit allen IT-Sicherheitsmaßnahmen im gesamten Cyber-Raum
- Cyber-Raum: alle mit dem globalen Internet verbundenen IT-Systeme und -Infrastrukturen
- Ziel: Schutz vor Verlust von Vertraulichkeit, Authentifikation, Authentizität, Integrität, Verbindlichkeit, Verfügbarkeit und Anonymisierungs/Pseudonymisierung

![Cyber-Sicherheit](./cyber-sicherheit-zusammenhang.png)
[Cyber-Sicherheit, Norbert Pohlmann](https://norbert-pohlmann.com/glossar-cyber-sicherheit/cyber-sicherheit-2/)


## Bereiche der Cyber Security

1. ### Netzwerksicherheit

   `Was ist das?` Schutz von Computernetzwerken vor unbefugtem Zugriff, Missbrauch und Angriffen.
   `Beispiel:` Eine Firewall auf einem Heimrouter blockiert unautorisierte Verbindungsversuche aus dem Internet und verhindert, dass Hacker auf das Heimnetzwerk zugreifen.
   `Wie:`

   - Firewalls: Schützen Netzwerke, indem sie eingehenden und ausgehenden Datenverkehr überwachen und Regeln anwenden, um Angriffe abzuwehren.
   - Intrusion Detection Systems (IDS) & Intrusion Prevention Systems (IPS): Erkennen und verhindern potenziell schädliche Aktivitäten im Netzwerk.
   - Virtual Private Networks (VPNs): Bieten eine sichere Verbindung über unsichere Netzwerke, wie das Internet, indem sie den Datenverkehr verschlüsseln.

2. ### Anwendungssicherheit

   `Was ist das?` Sicherstellung, dass Softwareanwendungen frei von Schwachstellen sind, die von Angreifern ausgenutzt werden könnten.
   `Beispiel:` Ein Online-Shop überprüft sorgfältig alle Eingaben in Suchfelder, um sicherzustellen, dass niemand schädlichen Code einschleusen kann (z. B. durch SQL-Injection).
   `Wie:`

   - Sichere Softwareentwicklung: Implementierung von Sicherheitspraktiken während des gesamten Softwareentwicklungsprozesses, um Schwachstellen zu minimieren (z. B. OWASP Top 10 (=Open Web Application Security Projekt)).
   - Penetrationstests: Simulierte Angriffe auf Anwendungen, um Schwachstellen zu identifizieren und zu beheben.
   - Code Reviews & Static Analysis Tools: Überprüfung von Quellcode auf potenzielle Sicherheitslücken.

3. ### Endpunktsicherheit

   `Was ist das?` Schutz von Geräten, die mit einem Netzwerk verbunden sind, wie Computer, Smartphones und Tablets.
   `Beispiel:` Ein Antivirus-Programm auf einem Laptop erkennt und blockiert einen heruntergeladenen Virus, bevor er Schaden anrichten kann.
   `Wie:`
   - Antivirus/Antimalware-Software: Schutz von Endgeräten (z. B. PCs, Laptops, Smartphones) vor Schadsoftware.
    - Endpoint Detection and Response (EDR): Fortgeschrittene Tools, die Bedrohungen auf Endgeräten erkennen und darauf reagieren können.
    - Device Management: Verwaltung von Sicherheitsrichtlinien und Software auf Endgeräten.

4. ### Identitäts- und Zugriffsmanagement (IAM)

   `Was ist das?` Verwaltung von Benutzeridentitäten und Kontrolle, wer auf welche Ressourcen zugreifen darf.
   `Beispiel:` Bei einer Bank-App wird eine Zwei-Faktor-Authentifizierung verwendet, bei der der Benutzer neben dem Passwort auch einen Code eingeben muss, der auf sein Handy gesendet wird.
   `Wie:`

    - Multi-Factor Authentication (MFA): Verwendung mehrerer Authentifizierungsmethoden (z. B. Passwort und biometrische Daten), um die Sicherheit zu erhöhen.
    - Single Sign-On (SSO): Ermöglicht Benutzern den Zugriff auf mehrere Systeme mit einem einzigen Anmeldevorgang.
    - Privileged Access Management (PAM): Verwaltung und Überwachung von privilegierten Konten mit erweitertem Zugriff auf kritische Systeme.

5. ### Kryptographie

   `Was ist das?` Schutz von Informationen durch Verschlüsselung, sodass nur berechtigte Parteien Zugriff darauf haben.
   `Beispiel:` Wenn du eine Nachricht über einen sicheren Messenger wie WhatsApp sendest, wird diese verschlüsselt, sodass nur der Empfänger sie lesen kann.
   `Wie:`
   - Verschlüsselung: Schutz von Daten durch Umwandlung in eine unlesbare Form, die nur mit einem Schlüssel wiederhergestellt werden kann.
    - Public Key Infrastructure (PKI): Verwaltung von digitalen Zertifikaten und öffentlichen Schlüsseln, um sichere Kommunikation und Authentifizierung zu gewährleisten.
    - Hashing: Erzeugung eines eindeutigen, festen Datenwerts aus beliebigen Daten, der als Fingerabdruck dieser Daten verwendet wird.

6. ### Bedrohungsanalyse und -management

   `Was ist das?` Erkennung und Reaktion auf potenzielle Sicherheitsbedrohungen.
   `Beispiel:` Ein Unternehmen verwendet ein Überwachungssystem, das ungewöhnliche Aktivitäten auf seinen Servern erkennt und Alarm schlägt, wenn ein potenzieller Angriff entdeckt wird.
   `Wie:`
   - Threat Intelligence: Sammlung und Analyse von Informationen über aktuelle Bedrohungen, um Angriffen vorzubeugen.
    - Security Information and Event Management (SIEM): Tools, die Daten aus verschiedenen Quellen sammeln, um Anomalien zu erkennen und auf Bedrohungen zu reagieren.
    - Incident Response: Prozesse zur Erkennung, Analyse und Reaktion auf Sicherheitsvorfälle.

7. ### Risikomanagement und Compliance

   `Was ist das?` Identifizierung und Verwaltung von Sicherheitsrisiken sowie Einhaltung gesetzlicher Vorschriften.
   `Beispiel:` Eine Firma bewertet, welche Daten besonders schützenswert sind, und setzt entsprechende Sicherheitsmaßnahmen ein, um den Verlust dieser Daten zu verhindern.
   `Wie:`
    - Risikobewertung: Identifizierung und Bewertung von Risiken, um geeignete Sicherheitsmaßnahmen zu ergreifen.
    - Regulatorische Compliance: Einhaltung von gesetzlichen und branchenspezifischen Sicherheitsanforderungen (z. B. GDPR, ISO 27001).
    - Business Continuity Planning (BCP) & Disaster Recovery (DR): Strategien zur Sicherstellung des Geschäftsbetriebs im Falle eines Sicherheitsvorfalls oder einer Katastrophe.

8. ### Phishing und Social Engineering

   `Was ist das?` Angriffe, bei denen Menschen durch Täuschung dazu gebracht werden, vertrauliche Informationen preiszugeben oder schädliche Aktionen auszuführen.
   `Beispiel:` Eine Person erhält eine gefälschte E-Mail, die wie eine Nachricht von ihrer Bank aussieht, und wird aufgefordert, ihre Anmeldedaten einzugeben, die dann von den Angreifern gestohlen werden.
   `Wie:`
   - Phishing Awareness Training: Schulungen, um Benutzer über die Gefahren von Phishing und Social Engineering zu informieren und ihnen beizubringen, wie sie solche Angriffe erkennen und vermeiden können.
    - Social Engineering Tests: Simulierte Angriffe, um die Reaktionsfähigkeit der Benutzer auf manipulative Taktiken zu testen.

9. ### Cloud-Sicherheit

   `Was ist das?` Schutz von Daten, Anwendungen und Diensten, die in der Cloud gehostet werden.
   `Beispiel:` Ein Unternehmen verwendet eine Cloud-Plattform wie AWS und sorgt dafür, dass alle Daten, die in der Cloud gespeichert sind, verschlüsselt und nur für autorisierte Benutzer 
   zugänglich sind.
   `Wie:`
    - Shared Responsibility Model: Verteilung der Sicherheitsverantwortungen zwischen dem Cloud-Anbieter und dem Kunden.
    - Cloud Access Security Brokers (CASB): Tools, die Sicherheitsrichtlinien zwischen den Cloud-Nutzern und Cloud-Anbietern durchsetzen.
    - Cloud Security Posture Management (CSPM): Tools zur kontinuierlichen Überwachung und Durchsetzung von Sicherheitsrichtlinien in Cloud-Umgebungen.

10. ### Datensicherheit und Datenschutz

    `Was ist das?` Schutz sensibler Informationen vor unbefugtem Zugriff und Missbrauch.
    `Beispiel:` Ein Arzt verwendet eine spezielle Software, die Patientendaten verschlüsselt speichert, sodass nur medizinisches Fachpersonal mit den richtigen Berechtigungen darauf zugreifen kann.
    `Wie:`
    - Data Loss Prevention (DLP): Schutz von sensiblen Daten vor unbeabsichtigtem Verlust oder Diebstahl.
    - Datenschutz-Grundverordnung (DSGVO): Europäische Verordnung zum Schutz personenbezogener Daten.
    - Verschlüsselung & Tokenisierung: Techniken zur Sicherung sensibler Daten, insbesondere bei Speicherung und Übertragung.

11. ### Supply Chain Security (Lieferkettensicherheit)

    `Was ist das?` Schutz der gesamten Lieferkette, die an der Erstellung und Bereitstellung von Produkten und Dienstleistungen beteiligt ist, um sicherzustellen, dass keine bösartigen Elemente in den Prozess eingeführt werden.
    `Beispiel:` Ein Softwareunternehmen überprüft alle Bibliotheken von Drittanbietern, die in seiner Software verwendet werden, um sicherzustellen, dass keine davon kompromittiert ist.
    `Wie:`

--- 
## Bedrohungen

### 1. Warum ist Cybersecurity wichtig?
- Schaden an verschiedenen Stellen:
    - Unternehmen
    - Staaten
    - lokale Gemeinschaften
    - private Personen
- Beispiele:
    - Identitätsdiebstahl
    - Erpressung
    - Verlust sensibler Informationen oder geschäftskritischer Daten
    - Verlust von Aufträgen/ Kunden - Geschäftsschließungen
- durschnittliche Kosten eines Data Breachs 4,88 Mio. USD in 2024
    - Anstieg von 10% zum Vorjahr
- Anzahl der Unternehmen, die wegen daraus resultierender Datenschutzverletzung Bußgelder zahlen mussten:
    - die mehr als 50.000 USD betrugen, stieg um **22,7%** im Vergleich zum Vorjahr
    - die mehr als 100.000 USD betrugen, stieg um **19,5%** im Vergleich zum Vorjahr           

### 2. Arten von Cyberbedrohungen

#### Allgemein
- Zunahme von Cloud Computing
    - Komplexität Netzwerkverwaltung und Risiko Fehlkonfiguation
    - Unzureichende Sicherung und Schwachstellen
- Steigende Zahl von Remote- & Hybridarbeit, sowie _Bring-your-own-Device_ Richtlinien
    - Unternehmen müssen mehr Verbindungen und Geräte sichern
    - Anwendungen und Daten schützen
- Vebreitung Internet of Things
    - Verbindung zu Haushaltsgeräten
    - standardmäßig meist nicht oder unzureichend gesichert
- Aufstieg der künstlichen Intelligenz und generative KI
    - Prompt Injection
    - Manipulation von generativer KI
    - vertrauliche Daten herausgeben oder Falschinformationen verbreiten

#### Cyberkriminalität
- einzelne Akteure oder Gruppen
- finanzieller Anreiz
    - private Nutzer
    - Unternehmen
- Geschäftsbetrieb unterbrechen/ behindern

#### Cyberangriffe
- politisch motiviert
- Informationsbeschaffung
- Unternehmen oder staatliche Einrichtungen

#### Cyberterrorismus
- Systeme werden unterwandert
- Informationsbeschaffung, laufender Betrieb wird behindert
- soll Angst verbreiten oder Panik auslösen

### 3. Malware und Methoden

![Grafik mit vercshiedenen Malwares und Methoden](https://www.acatech.de/wp-content/uploads/2023/04/23_aaD_Cybersicherheit_N.png)
> Quelle: [acatech.de](https://www.acatech.de/allgemein/acatech-am-dienstag-cybersicherheit/)

| Malware _malicious software_ | Bechreibung |
| - | - |
| Virus | selbst replizierend, vebreitet sich und infiziert Dateien mit schädlichem Code |
| Trojaner | Tarnung als vertrauenswürdige Software, Datensammlung |   
| Spyware | prokolliert Eingaben des Nutzers |
| Ransomware | blockiert Dateien und Daten eines Nutzers |
| Adware | Verbreitung von Schadsoftware über Werbesoftware |
| Botnets | Computernetzwerke befallen mit Schadsoftware, werden genutzt um Online-Aufgaben ohne Einvertsändnis des Nutzers auszuführen |

| Weitere Methoden | Beschreibung |
| - | - |
| Phishing | E-Mail, Text- oder Sprachnachrichten verleiten zum Download von Malware, Ausgabe von vertraulicher Daten oder Geldtransaktionen |
| SQL Injection | Kontrolle über Daten aus Datenbank erhalten, über speziellen SQL-Befehl wird Schadcode in Datenbank eingefügt | 
| Man-in-the-Middle-Angriff | Abfangen von Informationen zwischen zwei Beteiligten, Bspw. über ungesichertes W-LAN Netz |
| Distributed-Denial-of-Service (DDoS) Angriff | Überschwemmung mit Datenverkehr, sodass System handlungsunfähig wird |
| Romance-Scamming | Vorgeben von Partnersuche, Preisgabe persönlicher Daten oder finanzieller Mittel |
| Kryptojacking | Zugriff auf Endgerät zur Nutzung von Rechenleistung, um Kryptowährung zu schürfen |
| Kompromittierung von geschäftlichen E-Mails (BEC) | Vortäuschung (oft über E-Mail) eine vertraute Person zu sein: Chef, Mitarbeiter, Lieferanten oder Geschäftspartner |
| Kompromittierung von E-Mail-Konten (EAC) | Ähnlich BEC, doch hier wird das Konto wirklich übernommen und gesteuert |
| Social-Engineering-Angriffe _(allgemein)_ | Menschen beeinflussen, damit sie sensible, vertrauliche Informationen preisgeben, um Geld zu verdienen oder Zugang zu Daten zu erhalten |

### 4. Endbenutzer
- Einzelpersonen werden angegriffen
- Durch Unwissenheit Malware oder andere Cyberbedrohungen auf Geräte laden
- Besonders Nutzer mit vielen Zugriffsrechten gefährdet

> Quellen:
[ibm.com](https://www.ibm.com/de-de/topics/cybersecurity)
[kasperky.de](https://www.kaspersky.de/resource-center/definitions/what-is-cyber-security)
[proofpoint.com](https://www.proofpoint.com/de/threat-reference/cybersecurity-network-security)
[sap.com](https://www.sap.com/swiss/products/financial-management/what-is-cybersecurity.html)
[acatech.de](https://www.acatech.de/allgemein/acatech-am-dienstag-cybersicherheit/)

---
## Best Practices / Tools / Technologien

### 1. Best Practices (Beste Praktiken)
Dieser Abschnitt umfasst die Methoden und Strategien, die für einen effektiven Schutz von Informationen und Systemen vor Cyber-Bedrohungen verwendet werden. Einige der besten Praktiken umfassen:

- **Verwendung von starken Passwörtern und deren Verwaltung**: Erstellung komplexer Passwörter und Verwendung von Passwort-Managern zur sicheren Speicherung.

- **Zwei-Faktor-Authentifizierung (2FA)**: Hinzufügen einer zusätzlichen Sicherheitsebene für den Zugriff auf Konten.

- **Regelmäßige Software-Updates**: Stellt sicher, dass Systeme vor bekannten Schwachstellen geschützt sind.

- **Regelmäßige Datensicherung**: Erstellung regelmäßiger Backups von Daten zur Wiederherstellung im Falle eines Angriffs oder Datenverlusts.

- **Benutzerschulung**: Schulung von Mitarbeitern und Nutzern zu Cyber-Bedrohungen wie Phishing und deren Abwehrmethoden.



### 2. Tools / Technologien (Werkzeuge und Technologien)
Im Bereich der Cybersicherheit werden verschiedene Werkzeuge und Technologien eingesetzt, um Systeme und Daten zu schützen. Einige der wichtigsten sind:

- **Antiviren- und Antimalware-Programme**: Software, die zur Erkennung und Entfernung von Malware verwendet wird.

- **Firewalls**: Hardware- oder Softwarelösungen, die den eingehenden und ausgehenden Netzwerkverkehr überwachen und kontrollieren.

- **Intrusion Detection und Prevention Systems (IDS/IPS)**: Werkzeuge zur Erkennung und Abwehr von Netzwerkangriffen.

- **VPN (Virtuelles privates Netzwerk)**: Eine Technologie, die zur Schaffung einer sicheren Verbindung zwischen Benutzer und Netzwerk verwendet wird.

- **SIEM (Security Information and Event Management)**: Werkzeuge zur Analyse von Sicherheitsprotokollen und zur Identifizierung von Bedrohungen.

- **Verschlüsselungstechnologie**: Verwendung von Verschlüsselungsalgorithmen zum Schutz von Informationen während der Übertragung oder Speicherung.



### 3. Anwender / Nutzer (Benutzer/Rolle der Benutzer)
Im Bereich der Cybersicherheit spielen die Benutzer eine entscheidende Rolle, da viele Cyber-Bedrohungen durch Benutzerfehler entstehen. Die Schulung und Sensibilisierung der Benutzer für Bedrohungen und Sicherheitsmaßnahmen ist eine der wichtigsten präventiven Maßnahmen. Dieser Abschnitt umfasst:

- **Schulung und Sensibilisierung**: Regelmäßige Schulungen zu Cyber-Bedrohungen wie Phishing, Social Engineering und zu deren Vermeidung.

- **Sichere Nutzungspolitiken**: Erstellung und Durchsetzung von Richtlinien für die sichere Nutzung von Unternehmenssystemen und -informationen.

- **Rolle im Schutz von Informationen**: Benutzer zur Einhaltung der besten Praktiken ermutigen, wie die Verwendung starker Passwörter und das Melden verdächtiger Aktivitäten.

- **Rollenbasierter Zugriff**: Beschränkung des Zugriffs auf Informationen und Systeme basierend auf den Rollen und Bedürfnissen der Benutzer, um interne Risiken zu minimieren.

Diese drei Abschnitte tragen gemeinsam zur Schaffung einer sicheren Cyber-Umgebung bei, in der geeignete Werkzeuge, moderne Technologien und gut informierte Benutzer eingesetzt werden, um Unternehmenssysteme und -informationen vor Bedrohungen zu schützen.
