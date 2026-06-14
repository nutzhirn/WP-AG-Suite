# Release-Strategie

## Versionierung

Empfohlen wird semantische Versionierung:

MAJOR.MINOR.PATCH

Beispiel:

2.3.4

## ZIP-Dateien

ZIP-Dateien sollen nach folgendem Schema benannt werden:

WP-AG-Suite-2.3.4.zip

## GitHub Releases

Jede stabile Version soll als GitHub Release veröffentlicht werden.

Ein Release sollte enthalten:

- Versionsnummer.
- Kurze Zusammenfassung.
- Changelog.
- ZIP-Datei.
- Hinweise zu bekannten Problemen.
- Upgrade-Hinweise, falls notwendig.

## Branches

Empfohlene Struktur:

- main: stabile Entwicklungsbasis.
- develop: laufende Entwicklung.
- release/x.y.z: vorbereitete Releases.
- hotfix/x.y.z: dringende Fehlerbehebungen.
