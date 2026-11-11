# Erkennungsliste für PC-Wartung

Diese Liste sagt dem Wartungsskript, welche Programme als Müll-Software gelten, welche Fernwartungs-Programme es meldet und bis wann eine Windows-Version Sicherheitsupdates bekommt.

- `definitionen.json`: die Liste
- `definitionen.json.sig`: die Signatur dazu

Das Skript verwendet die Liste nur, wenn die Signatur stimmt und alle Prüfungen bestehen. Sonst gilt die Liste, die im Skript eingebaut ist. Eine geänderte Datei ohne passende Signatur wird ignoriert.

Stufen in der Liste:

| Stufe | Bedeutung |
|---|---|
| A | wird still deinstalliert |
| B | wird nur gemeldet |
| AV | Virenschutz, wird nur gemeldet, wenn er abgelaufen oder inaktiv ist |

Fehlt etwas oder ist ein Eintrag falsch? Bitte ein Issue aufmachen.
