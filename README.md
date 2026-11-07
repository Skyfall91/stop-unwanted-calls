# Stop Unwanted Calls

Ein Agent Skill, der unerwünschte Anrufe untersucht und hilft, sie beim Verursacher abzustellen.

| Worum geht es? | Passender Skill |
|---|---|
| Werbeanrufe und Betrugsversuche am Telefon | **Stop Unwanted Calls** · `stop-unwanted-calls` |
| Spam, unerwünschte Newsletter und Phishing per Mail | [Stop Unwanted Email](https://github.com/Skyfall91/stop-unwanted-email) · `stop-unwanted-email` |

## Was der Skill macht

Er wertet Anruflisten aus Telefon, Router, Anbieterportal oder Export aus. Er prüft angezeigte und netzseitig übermittelte Rufnummern und wählt anhand der Belege zwischen einer Netzbetreiberanfrage, einem Werbewiderspruch und einer sachlichen Meldung. Bekannte Kontakte bleiben erreichbar. Wer kontaktiert werden darf und welche Angaben dabei sichtbar werden, richtet sich nach deiner Freigabe.

## Installieren

1. Lade das Repository über **Code → Download ZIP** herunter und entpacke es. Benenne den entpackten Ordner `stop-unwanted-calls`.
2. **Mit Agent-Skills-Unterstützung:** Füge den Ordner mit `SKILL.md` und `references/` über die Skill-Verwaltung deines Assistenten hinzu. Das Repository verwendet das offene [Agent-Skills-Format](https://agentskills.io/specification).
3. **Ohne Skill-Verwaltung:** Gib dem Assistenten `SKILL.md` und `references/source-remedies.md` als Dateien oder kopiere beide Texte in den Chat. Starte anschließend mit dem Beispiel unten.

## Ausprobieren

```text
Nutze den Skill „Stop Unwanted Calls“ für diese Anrufliste.
Finde heraus, wer hinter den Anrufen steckt, und bereite die passende
Maßnahme an der Quelle vor. Bekannte Kontakte sollen erreichbar bleiben.
Frag bei unklaren Anbietern einzeln nach. Keine lokalen Rufsperren.
Sag vor dem Versand, welche meiner Daten der Empfänger sehen würde.
```

## Zugriff und Ergebnis

Der Assistent braucht Zugriff auf die Anrufliste oder einen von dir bereitgestellten Auszug. Der Skill selbst enthält nur Anleitung und Vorlagen. Ohne freigegebenen Versandweg erstellt der Assistent einen Entwurf. Bei einer ausgeführten Aktion meldet er, was gesendet wurde und ob der Empfänger die Umsetzung bestätigt hat.
