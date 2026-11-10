# Changelog

## 0.4.5 · 10. November 2026

- Ausgaben und Fehler direkt aus der App an Zumbyte melden. Meldedialog mit bearbeitbarem Text und automatischer App-Version; technische Angaben sind abwählbar.
- Eigene Fehlerliste im Zumbyte-Adminbereich mit Status, Priorität und Bearbeitungsverlauf.
- HTML-Dateien werden vollständig erzeugt, geprüft, gespeichert und zurückgelesen. Bloße Erstellungsankündigungen gelten nicht mehr als fertiges Ergebnis.
- Keine feste Grenze für Werkzeugschritte pro Auftrag oder Teilaufgabe. Stopp bleibt jederzeit verfügbar.
- Angepinnte Projekte öffnen den zuletzt besuchten Chat; die Auswahl bleibt nach dem Neustart erhalten. Archivierte oder gelöschte Chats werden übersprungen.
- GPU-/CPU-Auswahl unter Einstellungen → Modelle → Rechenleistung. Die Anzeige zeigt die tatsächlich geladene Modellbelegung.
- Wiederholte Dialoge und Formularfelder in Mockups werden vor dem Speichern abgeglichen. Eindeutige Verweise bleiben bedienbar; unklare Zuordnungen gehen zur Korrektur zurück an das Modell.
- Kompakte einzeilige Suche und ausgefülltes Stoppsymbol.
- Zumbyte-Copyright in der Seitenleiste und im Installer. Eigener Infodialog mit Version, Herausgeber, Kontakt, Impressum, Datenschutz und mitgelieferten Lizenztexten.

## 0.4.4 · 10. November 2026

### Oberfläche

- Native Windows-App mit Projektordnern, Gesprächsansicht und Live-Vorschau.
- Seitenleiste, Chat und Vorschau lassen sich über ihre Trenner in der Breite anpassen.
- Eigene dunkle Kontextmenüs und Dialoge mit abgerundeten Rahmen, Schließen-Schaltfläche und Escape-Unterstützung.
- Datei- und Ordnerauswahl im gleichen Design wie die App.
- Schmale Scrollleisten und eine animierte Anzeige während laufender Aufträge.

### Chats und Projekte

- Chats erscheinen direkt unter ihrem Projektordner. Geöffnete und geschlossene Ordner bleiben beim nächsten Start so erhalten.
- Wichtige Chats und Projekte lassen sich im Bereich **Angeheftet** ablegen.
- Chats und Projekte können archiviert und aus dem **Archiv** wiederhergestellt werden.
- Dauerhaftes Löschen wird vorher bestätigt. Projektdateien bleiben auf dem Rechner erhalten.

### Mockups

- Navigation mit getrennten Inhaltsansichten sowie zentrierte, schließbare Dialoge.
- Entwürfe werden vor dem Speichern auf Menüwechsel, Dialogaktionen und die Darstellung in einem schmalen Fenster geprüft.
- Änderungen können einzelne Bestandteile eines vorhandenen Entwurfs betreffen. Schlägt eine Überarbeitung fehl, bleibt die letzte funktionierende Vorschau erhalten.
- Die Vorschau kann über **Im Browser öffnen** außerhalb der App betrachtet werden.

### Installation und Updates

- Installer mit frei wählbarem Programmordner, getrennten Datenordnern und Desktopverknüpfung.
- Neue Versionen können unter **Einstellungen → Updates** heruntergeladen und installiert werden. Ein GitHub-Konto ist dafür nicht nötig.
- Vor dem Installieren wird geprüft, ob der Download vollständig und unverändert ist.
- Der Abbruch bei einer frischen Installation durch einen vermeintlich belegten Cacheordner wurde behoben.

[Version 0.4.4 herunterladen](https://github.com/ZUMBYTE-AppSolution/ownllm-release/releases/tag/v0.4.4)
