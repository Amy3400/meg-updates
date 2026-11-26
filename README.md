# MEG – Updates und freiwillige Testversionen

Hier liegen die signierten Android-Installationspakete für den gemeinsamen MEG-Updater. Quellcode, Signierschlüssel und persönliche Daten sind **nicht** in diesem öffentlichen Repository enthalten.

## Aktuelle freiwillige Testausgabe

**MEG 0.5.43 · Build 59** ist für den gemeinsamen Praxistest von Amy und Matze verfügbar. Diese Ausgabe ist **keine abgeschlossene stabile Version**; die Zwei-Geräte-Funktionsabnahme ist noch offen.

- [Release und Hinweise](https://github.com/Amy3400/meg-updates/releases/tag/v0.5.43)
- [Android-APK](https://github.com/Amy3400/meg-updates/releases/download/v0.5.43/MEG-v0.5.43.apk)
- [SHA-256-Datei](https://github.com/Amy3400/meg-updates/releases/download/v0.5.43/MEG-v0.5.43.sha256)
- [Gemeinsame Testanleitung](https://github.com/Amy3400/meg-updates/releases/download/v0.5.43/TESTANLEITUNG.md)

SHA-256 der APK: `a49d5361238d6653316c5245ad6f43c1dee39ebef0dea742f1c096b2f7961c57`.

## Freiwillig über MEG aktualisieren

1. **Einstellungen → Über MEG → Nach Update suchen** öffnen.
2. Das Angebot **0.5.43 (Build 59)** bewusst auswählen.
3. Je nach bisheriger MEG-Version öffnet sich der Browser oder der bisherige Download-/Installationsdialog. Bei Problemen den öffentlichen APK-Link oben nutzen.
4. Die bestehende MEG-App **niemals deinstallieren oder App-Daten löschen**. Das APK als Update installieren und nach dem Start Version und eigene Daten prüfen.
5. Bei Play-Protect-Blockierung, Signaturkonflikt oder unerwartetem Datenverlust **abbrechen und melden**; Schutzmechanismen nicht umgehen.

## Sicherheits- und Funktionsstand

Die 0.5.43-APK wurde unverändert aus dem signierten privaten Testkandidaten übernommen. Vor der Freigabe wurden die ursprüngliche SHA-256-Prüfsumme, das Paket `de.meg.assistant`, Version, Produktionssignatur und die öffentliche Download-Datei überprüft. Der eingebettete APK-Installer und seine Android-Berechtigung `REQUEST_INSTALL_PACKAGES` wurden aus **0.5.43** entfernt.

Die neuen MEG-Versionen prüfen weiterhin auf Updates, öffnen aber nur noch die GitHub-Seite für den manuellen Download. Ältere, bereits installierte MEG-Versionen können noch die frühere Installationsoberfläche enthalten.

Google Play Protect hat die 0.5.43-APK auf Amys Gerät als *anscheinend sicher* eingestuft. Das ersetzt keine vollständige Sicherheitsprüfung. Kalender, Familie, Freigaben, Widgets und Bridge V2 müssen noch gemeinsam auf beiden echten Geräten geprüft werden. Für die ersten Versuche ausschließlich eindeutig erkennbare Testdaten verwenden.

**Keine Pflichtinstallation, keine stille Aktualisierung und keine Freigabe als stabile Endversion.** Das Update-Manifest enthält `mandatory: false`; es werden keine kostenpflichtigen KI-Dienste neu aktiviert.
