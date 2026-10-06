# MEG Updates

Dieses öffentliche Repository enthält ausschließlich die Dateien, die MEG für seinen Update-Mechanismus benötigt.

Öffentlich sind:
- `update.json` mit Versionsnummer, Release-Hinweisen, Downloadadresse und SHA-256-Prüfsumme.
- signierte MEG-APK-Dateien als GitHub-Release-Assets.
- zugehörige SHA-256-Dateien.

Nicht hier enthalten sind der MEG-Quellcode, private Release-Informationen, Signierschlüssel oder Nutzerdaten.

Ab MEG 0.5.9 lädt die App verfügbare APK-Updates direkt von diesem Repository, prüft vor der Installation die veröffentlichte SHA-256-Prüfsumme und übergibt die verifizierte APK anschließend an Androids Installationsdialog.
