# WP-AG Suite – Kanonische Roadmap

## Bestand

### Dashboard

Zentrale Verwaltungsoberfläche der Suite. Das Dashboard soll Modulstatus, Systemzustand, wichtige Hinweise, Warnungen und schnelle Zugänge zu den Werkzeugen anzeigen.

### Diagnose

Analyse der WordPress-Installation, PHP-Version, Serverkonfiguration, Datenbank, Upload-Verzeichnisse, Cache-Situation, Objektcache und Systemumgebung.

### Security Check

Prüfung sicherheitsrelevanter WordPress-Konfigurationen und Hinweise auf typische Risiken.

### Beitragsimport

Import von WordPress-Beiträgen aus bestehenden Installationen. Der Import soll Autoren, Medien, Metadaten, Veröffentlichungsdatum, Kategorien, Schlagwörter und künftig Kommentare berücksichtigen.

### BookViewer

Darstellung und Verwaltung von PDF-Dokumenten als blätterbare Bücher oder Dokumentansichten. Ziel ist eine digitale Bibliothek innerhalb von WordPress.

### MediaInspector

Analyse der Mediathek, Prüfung verwendeter und nicht verwendeter Medien, Unterstützung bei Bereinigung und Archivierung.

### BackupManager

Werkzeuge für Backup und Wiederherstellung.

### Contacts

Kontaktverwaltung mit CSV- und VCF-Perspektive sowie späterer Erweiterung zur Adressverwaltung.

### PostTools

Werkzeuge für Beiträge, Kopieren, Bearbeiten und administrative Inhaltsaktionen.

### RevisionManager

Verwaltung und Bereinigung von WordPress-Revisionen.

### FontForce

Lokale Bereitstellung und Erzwingung definierter Schriften.

### MenuSearch

Such- und Verwaltungswerkzeuge für WordPress-Menüs.

### KatCloud

Kategorie-Cloud und Inhaltsnavigation.

### Artikelarchiv

Archiv- und Widgetfunktion für Beiträge.

### ThemeCleaner

Analyse und Bereinigung von Theme-relevanten Altlasten.

### Object Cache Analyse

Analyse von Objektcache, Drop-in-Dateien und Serverkonfiguration.

## Geplante Erweiterungen

### Seitenimport

Neben Beiträgen sollen auch WordPress-Seiten importiert werden können. Der Import soll Seitenhierarchien, Templates, Metadaten, Autoren, Medien und Veröffentlichungsstatus berücksichtigen.

### Erweiterte Migration

Langfristig soll WP-AG Suite nicht nur einzelne Inhalte, sondern komplette WordPress-Migrationen unterstützen. Dazu gehören Beiträge, Seiten, Kommentare, Medien, Benutzer, Taxonomien, Menüs und Metadaten.

### Kommentarimport

Kommentare sollen beim Import optional übernommen werden. Die Zuordnung zu Beiträgen und Benutzern muss nachvollziehbar erfolgen.

### Benutzer-Mapping

Beim Import muss sichtbar sein, welche Autoren oder Benutzer im Zielsystem fehlen. Fehlende Benutzer sollen während des Imports angelegt und anschließend korrekt zugeordnet werden können.

### PDF-zu-BookViewer-Konvertierung

Importierte PDF-Dateien sollen optional automatisch zu BookViewer-Einträgen konvertiert werden.

Konfigurationsfrage im Importdialog:

"Sollen die importierten PDFs gleich zu BookViewer-PDFs konvertiert werden?"

Die Konvertierung soll optional sein und nicht erzwungen werden.

### Avatar Modul

Ein Modul zur Erzeugung und Verwaltung von Benutzeravataren aus hochgeladenen Bildern. Avatare sollen WordPress-Benutzern zugeordnet werden können.

### Image Handling

Erweiterte Bildverwaltung mit ALT-Texten, Bildbeschreibungen, Copyright, Lizenzinformationen, Urheberangaben, Metadatenbearbeitung und Qualitätsprüfung.

### Akkordeon Generator

Ein Generator, der aus hochgeladenem oder eingefügtem Text WordPress-Akkordeons erzeugen kann. Überschriftenhierarchien sollen erkannt und als Akkordeonstruktur interpretiert werden.

### Image Resizer

Browserbasierter Bildzuschnitt und Export für Social Media und Webformate. Die Verarbeitung soll möglichst lokal erfolgen und keine Serveruploads benötigen.

Zielplattformen:

- Instagram
- Facebook
- TikTok
- YouTube
- LinkedIn
- Webformate

### Child Theme Generator

Erzeugung von Child Themes direkt aus WordPress heraus. Dazu gehört eine verständliche Hilfe, warum Child Themes sinnvoll sind und wann sie verwendet werden sollten.

### Activity Log / Audit Log

Protokollierung von fehlgeschlagenen Anmeldeversuchen, Benutzeranmeldungen, Benutzerabmeldungen, Benutzeraktivitäten, Änderungen an Beiträgen, Seiten, Plugins, Themes und Einstellungen.

Funktionen:

- Echtzeit-Aktivitätsüberwachung.
- Fehleranalyse vor Ausfällen.
- Sicherheitsüberwachung.
- Compliance-Unterstützung.
- Verantwortlichkeit und Nachvollziehbarkeit.
- Filter und Suche.
- Export von Protokollen.
- Einfache Einrichtung.

### Adressverwaltung

Korrekte Behandlung, Prüfung und Konversion von Adressen. Import und Export sollen langfristig auch VCF berücksichtigen.

### Socializer

Perspektivisch ein Modul für Social-Media-Veröffentlichung und Integration.

### Performance & Diagnostics Center

Erweiterter Analysebereich für Server, WordPress, Datenbank, Frontend, Cache, Performance-Scoring, Optimierungsempfehlungen und Performance-Historie.

### Website Quality Report

Konsolidierter Qualitätsbericht für Compliance, Barrierefreiheit, Performance, Sicherheit und Dokumentation.
