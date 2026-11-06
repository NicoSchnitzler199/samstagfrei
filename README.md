# Samstagfrei

Angebote, Rechnungen und Kalkulation für Handwerksbetriebe. Läuft auf Ihrem Windows-PC.

## Herunterladen

Unter **[Releases](https://github.com/NicoSchnitzler199/samstagfrei/releases/latest)** die neueste Datei `Samstagfrei-Setup-<Version>.exe` herunterladen.

## Installieren

1. Doppelklick auf `Samstagfrei-Setup-<Version>.exe`.
2. Erscheint die blaue Meldung „Der Computer wurde durch Windows geschützt“: auf **Weitere Informationen** klicken, dann auf **Trotzdem ausführen**. Die Meldung kommt, weil der Installer noch nicht signiert ist.
3. Dem Installer folgen. Samstagfrei startet danach im Browser.

Die ausführliche Anleitung liegt als PDF beim jeweiligen Release (`installation-und-smartscreen.pdf`, `startklar-in-15-minuten.pdf`).

### Datei prüfen (optional)

Jedes Release enthält `SHA256SUMS.txt`. In der PowerShell:

```
Get-FileHash .\Samstagfrei-Setup-<Version>.exe
```

Die angezeigte Zahl muss mit der in `SHA256SUMS.txt` übereinstimmen.

## Testen und freischalten

- Ohne Schlüssel startet eine **Testphase von 7 Tagen**. Belege tragen dann das Wasserzeichen MUSTER, Versand und Export sind gesperrt.
- Nach dem Kauf erhalten Sie per E-Mail einen Lizenzschlüssel (`SF1-…`). Eintragen unter **Einstellungen → Lizenz → Freischalten**.
