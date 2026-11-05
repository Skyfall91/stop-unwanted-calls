# FRITZ!Box Spam Source Stop

Ein Codex-Skill zum Untersuchen und Abstellen unerwünschter Werbeanrufe an der Quelle.

Der Ablauf nutzt die Anrufdaten einer FRITZ!Box als Belege, prüft die tatsächliche Betreiberzuordnung und bereitet Werbewidersprüche, Auskunftsanfragen oder sachliche Beschwerden vor. Er schützt bekannte Kontakte und berücksichtigt gemeinsam genutzte Haushaltsanschlüsse. Lokale Rufsperren sind kein Ersatz für das gewünschte Vorgehen.

## Installation

Dieses Repository als Ordner `fritzbox-spam-source-stop` in das eigene Skills-Verzeichnis kopieren, standardmäßig `~/.codex/skills/`. Die Datei `SKILL.md` liegt direkt darin. Bestehende Installationen vor dem Ersetzen prüfen.

## Verwendung

```text
Nutze $fritzbox-spam-source-stop. Finde die Quelle meiner Werbeanrufe.
Keine Nummern blockieren. Frag mich bei jedem Anbieter einzeln,
ob ich dessen Anrufe noch brauche. Eindeutige Betrugsversuche ablehnen.
```

Für den Routerzugriff wird ein passendes verbundenes Werkzeug oder Browser-/Computerzugriff benötigt. Für Nachrichten und Beschwerden ist ein verfügbarer Versandweg erforderlich. Der Skill enthält keine Zugangsdaten und erteilt keine zusätzlichen Berechtigungen.

Nummernanzeigen und Bewertungsportale beweisen keine Betreiberidentität. Ein versendeter Widerspruch ist noch keine bestätigte Einstellung der Anrufe. Der Skill verspricht keine vollständige Spamfreiheit und enthält keine privaten Fall- oder Anrufdaten.
