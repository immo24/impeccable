# Hinweise zu diesem Fork

Fork von [pbakaus/impeccable](https://github.com/pbakaus/impeccable), angelegt am 19.08.2026 als Sicherung fuer den Coder-Workspace.

Abweichung vom Original: In `plugin/skills/impeccable/scripts/context.mjs` steht `CHECK_INTERVAL_MS` auf 30 Tage statt auf 24 Stunden. Der Update-Check gegen impeccable.style laeuft damit einmal im Monat statt taeglich. Telemetrie und Konzept-API bleiben eingeschaltet.

Abgleich mit dem Original: `gh repo sync immo24/impeccable`. Danach diese Zeile pruefen, sie kollidiert mit Aenderungen des Anbieters an derselben Stelle.

Abschalten liesse sich der Netzverkehr komplett ueber die Umgebungsvariablen `DO_NOT_TRACK`, `IMPECCABLE_NO_TELEMETRY` und `IMPECCABLE_NO_UPDATE_CHECK`.
