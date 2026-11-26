# Sprecherprotokoll vorbereiten – Downloads

Dieses Repository dient ausschließlich der Verteilung freigegebener Programmdateien von „Sprecherprotokoll vorbereiten“. Es enthält keinen Quellcode.

## Aktuelle Version herunterladen

Aktuelle Version: **4.1.4** – für macOS und Windows mit demselben Funktionsumfang.

**Systemvoraussetzungen:** Mac mit Apple-Chip (M1 oder neuer) und macOS 13 (Ventura) oder neuer – Intel-Macs werden nicht unterstützt; 64-Bit-Windows 10 (ab Version 1809) oder Windows 11.

- **macOS:** [Sprecherprotokoll-macOS.dmg](https://github.com/SaskiaNoga/Sprecherprotokoll-Downloads/releases/latest/download/Sprecherprotokoll-macOS.dmg) – öffnen, „Sprecherprotokoll vorbereiten“ auf „Programme“ ziehen und aus „Programme“ starten (nicht direkt aus dem Download); die Anleitung „Bitte zuerst lesen“ liegt im selben Fenster
- **Windows:** [Sprecherprotokoll-Windows.exe](https://github.com/SaskiaNoga/Sprecherprotokoll-Downloads/releases/latest/download/Sprecherprotokoll-Windows.exe) – eine einzelne Programmdatei ohne Installation: in einem festen Ordner speichern und per Doppelklick starten; nach dem ersten Beenden heißt sie im selben Ordner „Sprecherprotokoll vorbereiten.exe“
- **Kurzanleitung (PDF):** [Sprecherprotokoll-Kurzanleitung.pdf](https://github.com/SaskiaNoga/Sprecherprotokoll-Downloads/releases/latest/download/Sprecherprotokoll-Kurzanleitung.pdf) – die wichtigsten Schritte zum Nachlesen

Die Downloaddateien heißen immer `Sprecherprotokoll-macOS.dmg` und `Sprecherprotokoll-Windows.exe`; das installierte Programm heißt auf beiden Systemen „Sprecherprotokoll vorbereiten“ (ohne Versionsnummer, die Version steht in der Seitenleiste).

Handbuch und Kurzanleitung sind außerdem im Programm enthalten und ohne Internet verfügbar (Hilfe → „Anleitungen (PDF) …“: öffnen oder als PDF speichern).

## Erstes Öffnen: Sicherheitsfreigabe (einmalig)

Das Programm ist für den Einsatz innerhalb der Fraktion bestimmt und nicht über Apple bzw. Microsoft beglaubigt (keine kostenpflichtige Notarisierung). Deshalb fragt das Betriebssystem beim ersten Öffnen einer selbst heruntergeladenen Version einmalig nach. Das ist erwartet und kein Zeichen für einen Fehler. Die Echtheit der Updates sichert unabhängig davon eine eigene digitale Signatur.

**macOS**

1. „Sprecherprotokoll vorbereiten“ aus dem Ordner „Programme“ öffnen.
2. Die Meldung „… kann nicht geöffnet werden“ mit **„Fertig“** schließen (nicht „In den Papierkorb legen“).
3. Apple-Menü → **Systemeinstellungen** → **Datenschutz & Sicherheit** → ganz nach unten scrollen.
4. Bei „Sprecherprotokoll vorbereiten wurde blockiert …“ auf **„Dennoch öffnen“** klicken und mit dem Mac-Passwort bestätigen.
5. Das Programm erneut öffnen und **„Öffnen“** wählen. Danach startet es ohne weitere Rückfrage, auch nach Updates.

Erscheint nur das Symbol im Dock, aber kein Fenster, wartet die Meldung aus Schritt 2 noch auf eine Antwort – eventuell auf einem anderen Bildschirm oder Schreibtisch (Mission Control zeigt alle). Kann das Programm nach der Freigabe kein Fenster anzeigen, meldet es sich ab 4.1.2 nach einer Minute selbst; „Protokoll zeigen“ öffnet ein Startprotokoll ohne persönliche Daten zur Weitergabe an die Betreuung.

**Windows:** Bei „Windows hat den PC geschützt“ auf **„Weitere Informationen“** und dann **„Trotzdem ausführen“** klicken.

## Stammdaten

Seit Version 4.0.0 übernimmt die Anwendung Ausschüsse, Besetzungen und Funktionen automatisch aus dem zentralen, digital unterschriebenen Datenbestand – ohne Anmeldung. Die Bearbeitung ist berechtigten Personen vorbehalten. E-Mail-Adressen sind nur verschlüsselt enthalten und mit einem vertraulich weitergegebenen Freischaltcode lesbar; den Code fragt seit Version 4.1.0 auch der Einrichtungsassistent ab.

Neu in 4.1.4 (Korrekturversion): Startanzeige statt eines leeren Fensters und keine Startwarnung mehr, wenn das Programm bereits bedienbar ist; schnellerer und sicherer Start in iCloud- und OneDrive-Ordnern (vorübergehend nicht erreichbare Dateien werden nie ersetzt); macOS-Updates in iCloud-Ordnern prüfen die Signatur ab dem nächsten Update unabhängig von iCloud-Attributen; keine doppelten Datensicherungen nach Updates; vollständige Updatehistorie im Diagnoseprotokoll; Enthaltungen je Fraktion lassen sich unter macOS wieder bei jeder Fensterbreite eintragen; überarbeitete Abbildungen in Handbuch und Kurzanleitung.

Neu in 4.1.3 (Korrekturversion): Der Einrichtungsassistent schaltet in Schritt 3 die geschützten Kontaktdaten frei (freiwillig, Schaltfläche „Freischalten“) und ruft in Schritt 4 die Besetzungsdaten automatisch ab; nach Updates wird bei jedem Programmstart gesucht; einheitlicher Programmname „Sprecherprotokoll vorbereiten“ unter macOS und Windows; lokale Diagnoseprotokolle ohne persönliche Daten (Hilfe → „Protokollordner öffnen …“, Anhang bei „Problem melden“); unter Windows starten die Hilfsprogramme für Updates zuverlässig.

Neu in 4.1.2 (Korrekturversion): zuverlässiger Programmstart mit verständlicher Meldung, falls kein Fenster erscheinen kann; Hinweis beim Start direkt aus dem Download (macOS); Updates auf einem iCloud-Schreibtisch scheitern nicht mehr an einem Dateiattribut; die Seitenleiste zeigt den tatsächlichen Updatestatus.

Neu in 4.1.1 (Korrekturversion): Fenstertitel „Fraktion & Ausschüsse anzeigen“ bzw. „… bearbeiten“, vollständige Texte unter Windows, früheres Antragsverfahren vollständig entfernt. Seit 4.1.0 liegen alle Verwaltungsfunktionen in der „Zentralen Verwaltung“ mit Seitenleiste und Übersicht.

## Updates

Installierte Versionen ab 3.5.1 erkennen neue Versionen selbst und installieren sie erst nach Zustimmung – mit Datensicherung vorher und automatischer Rückkehr bei Fehlern. Bis 4.1.2 wird höchstens einmal täglich gesucht, ab 4.1.3 bei jedem Start; sofort geht es über „Einstellungen“ → „Programmupdates“ → „Auf Updates prüfen“.

**macOS, Programm in einem iCloud-Ordner (etwa auf dem Schreibtisch), Update auf 4.1.4:** Meldet das Update „Die Signatur der eingesetzten Version ist ungültig“, wurde die bisherige Version automatisch wiederhergestellt; ein erneuter Versuch über „Einstellungen“ → „Programmupdates“ ist gefahrlos.

**Windows, Update aus 4.1.2 oder älter:** Wird ein über „Jetzt aktualisieren“ gestartetes Update nicht abgeschlossen (das Programm startet nicht von selbst neu), 4.1.4 einmalig über den Link oben herunterladen und die bisherige `.exe` ersetzen. Alle Daten bleiben erhalten.

Zu jedem Release gehören `SHA256.txt` (Prüfsummen) und `update.json` (signierte Update-Informationen, die die Anwendung vor jeder Installation prüft).

## Frühere Versionen

Alle bisherigen Versionen bleiben unter [Releases](https://github.com/SaskiaNoga/Sprecherprotokoll-Downloads/releases) verfügbar.
