# Stop Unwanted Calls

Ein allgemeiner KI-Skill zum Untersuchen und Abstellen unerwünschter Werbeanrufe an der Quelle.

Der Ablauf nutzt Anrufdaten aus Telefon, Anbieterportal, Router oder einem bereitgestellten Export, prüft die tatsächliche Betreiberzuordnung und bereitet Werbewidersprüche, Auskunftsanfragen oder sachliche Beschwerden vor. Er schützt bekannte Kontakte und gemeinsam genutzte Haushaltsanschlüsse. Wenn der Nutzer die Weitergabe seiner Mailadresse oder von Bewohnernamen untersagt, gilt das auch für Absenderfelder, Formulare und Anhänge. Lokale Rufsperren sind kein Ersatz für das gewünschte Vorgehen.

## Mit beliebigen KI-Assistenten verwenden

Das Repository folgt dem offenen [Agent-Skills-Format](https://agentskills.io/specification): `SKILL.md` enthält die Anleitung, `references/source-remedies.md` die zusätzlichen Vorlagen und deutschen Beschwerdewege. Es setzt weder ein bestimmtes KI-Produkt noch ein bestimmtes Routermodell voraus.

Bei einem Assistenten mit Agent-Skills-Unterstützung den Ordner `stop-unwanted-calls` über dessen Skill-Verwaltung hinzufügen; Ablageort und Aktivierung richten sich nach dem jeweiligen Produkt.

Bei einem Assistenten ohne Skill-Verwaltung beide Markdown-Dateien als Anweisungen bereitstellen oder in den Chat einfügen. Das überträgt den Ablauf, fügt aber keine Werkzeuge oder Berechtigungen hinzu. Den Assistenten mit der folgenden Aufgabe starten.

## Verwendung

```text
Wende den beigefügten Skill „Stop Unwanted Calls“ an.
Finde die Quelle meiner Werbeanrufe.
Keine Nummern blockieren. Frag mich bei jedem Anbieter einzeln,
ob ich dessen Anrufe noch brauche. Eindeutige Betrugsversuche ablehnen.
Gib meine persönliche Mailadresse und Bewohnernamen nicht weiter.
```

Für direkten Zugriff auf Anrufdaten wird ein passendes verbundenes Werkzeug oder Browser-/Computerzugriff benötigt. Ohne diesen Zugriff arbeitet der Assistent mit bereitgestellten Daten. Für direkte externe Aktionen ist ein verfügbarer, genehmigter Kommunikationsweg erforderlich; sonst erstellt der Assistent konkrete Entwürfe und nennt die verbleibenden Schritte. Der Skill enthält keine Zugangsdaten und erteilt keine zusätzlichen Berechtigungen.

Nummernanzeigen und Bewertungsportale beweisen keine Betreiberidentität. Ein versendeter Widerspruch ist noch keine bestätigte Einstellung der Anrufe. Der Skill verspricht keine vollständige Spamfreiheit und enthält keine privaten Fall- oder Anrufdaten.
