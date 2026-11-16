# MEG – Updates und gemeinsame Testausgabe

Hier liegen die signierten Installationspakete für den MEG-Updater. Der Quellcode, Signierschlüssel und persönliche Daten sind nicht enthalten.

## Aktuelle freiwillige Testausgabe

**MEG 0.5.23 · Build 39** ist für den gemeinsamen Praxistest vorgesehen. Diese Ausgabe ist keine abgeschlossene stabile Gesamtversion.

- [Testausgabe, Änderungen und Downloads](https://github.com/Amy3400/meg-updates/releases/tag/v0.5.23)
- [Gemeinsame Testanleitung](https://github.com/Amy3400/meg-updates/releases/download/v0.5.23/TESTANLEITUNG.md)
- [APK herunterladen](https://github.com/Amy3400/meg-updates/releases/download/v0.5.23/MEG-v0.5.23.apk)
- [SHA-256-Prüfsumme](https://github.com/Amy3400/meg-updates/releases/download/v0.5.23/MEG-v0.5.23.sha256)

## Über MEG aktualisieren

1. MEG öffnen und unter **Einstellungen → Über MEG** nach Updates suchen.
2. Die Hinweise zu **0.5.23 / Build 39** lesen und das Update bewusst starten.
3. Die Installation im Android-Dialog bestätigen.
4. MEG wieder öffnen, Versionsnummer und bisherige Daten prüfen.
5. Für den Familientest zuerst beide Geräte aktualisieren und anschließend die gemeinsame Testanleitung durchgehen.

Die genaue Beschriftung der Updateprüfung hängt von der bisher installierten MEG-Version ab. Falls die Meldung „Automatische Updates noch nicht eingerichtet“ erscheint, kann die öffentliche APK oben als Update der vorhandenen App geöffnet werden.

**Die vorhandene MEG-App nicht deinstallieren und ihre Daten nicht löschen.** Eine vollständige Sicherungs-/Wiederherstellungsfunktion ist noch offen. Bei Installations-, Signatur- oder Play-Protect-Fehlern abbrechen und den genauen Hinweis melden. Ein Downgrade ist kein geprüfter Wiederherstellungsweg.

## Was vor der Bereitstellung geprüft wurde

Die APK wurde aus dem bereits erfolgreich geprüften GitHub-Testlauf übernommen. Paketname, Versionsnummer, Prüfsumme und Signatur wurden erneut kontrolliert. Die Signatur stimmt mit der öffentlichen MEG 0.5.22 überein. Die öffentlichen Downloads wurden vor der Umstellung des Updaters auf identische Dateien geprüft.

Die Prüfung auf den tatsächlichen Handys, Samsung-/One-UI-Widgets, Benachrichtigungen und gemeinsame Familienabläufe ist Teil dieses Tests und noch nicht abgeschlossen. Weitere bekannte Restfunktionen stehen in den Release-Hinweisen.

## Datenschutz und Installation

Das Update ist freiwillig und aktiviert keinen neuen kostenpflichtigen KI-Dienst. Bereits eingerichtete Cloud-Anbieter unterliegen ihren bisherigen Einstellungen und Bedingungen. Android entscheidet über die Installation; es gibt keine automatische stille Installation.

Die App liest `update.json`, lädt die öffentliche APK, prüft ihre SHA-256-Prüfsumme und öffnet danach Androids Installationsdialog. Die JSON-Datei und Release-Dateien enthalten keine Nutzerdaten.
