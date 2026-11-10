<p align="center"><img src="assets/app-icon.png" width="112" height="112" alt="OwnLLM Studio"></p>
<h1 align="center">OwnLLM Studio</h1>
<p align="center">Chats, Projekte, App-Entwürfe und Bilder auf deinem Rechner.</p>
<p align="center"><a href="https://github.com/ZUMBYTE-AppSolution/ownllm-release/releases/latest">Herunterladen</a> · <a href="CHANGELOG.md">Changelog</a> · <a href="https://github.com/ZUMBYTE-AppSolution/ownllm-release/issues">Fehler melden</a></p>

OwnLLM Studio ist ein lokaler Assistent für Windows. Du sammelst Gespräche in Projekten, arbeitest mit deinen Dateien und lässt dir App-Entwürfe als bedienbare Vorschau und Bilder aus einer Beschreibung erstellen. Das Sprachmodell läuft auf deinem Computer; Chats und Dateien werden in den von dir gewählten Ordnern gespeichert.

| Ausgabe | Download |
| --- | --- |
| Windows, 64 Bit | [Installer 0.4.6 herunterladen](https://github.com/ZUMBYTE-AppSolution/ownllm-release/releases/download/v0.4.6/OwnLLM-Studio-0.4.6-Windows-Setup.exe) |

Der Installer enthält die Programmdateien und bietet eine Desktopverknüpfung an. Ein Sprachmodell kann bei der Einrichtung zusätzlich heruntergeladen werden. Visual Studio oder andere Entwicklungswerkzeuge brauchst du für die Nutzung nicht.

## Einblicke

### Projektchats und angeheftete Gespräche

![OwnLLM Studio mit Projektordnern, angehefteten Chats und Gesprächsansicht](assets/screenshots/ownllm-workspace.png)

### Projekte bearbeiten und verwalten

| Projekthinweise | Kontextmenü |
| --- | --- |
| ![Projektnamen und Hinweise für das lokale Modell bearbeiten](assets/screenshots/ownllm-projekt-dialog.png) | ![Projekt anpinnen, bearbeiten, archivieren oder löschen](assets/screenshots/ownllm-kontextmenue.png) |

### App-Entwürfe ausprobieren

![Beispiel einer interaktiven Live-Vorschau mit Navigation, Tabelle und Aktionen](assets/screenshots/ownllm-mockup.png)

Die Bilder zeigen Beispielprojekte und einen lokal erzeugten App-Entwurf. Die Partitionsverwaltung ist eine Vorschau; sie verändert keine Datenträger.

## Das kannst du mit OwnLLM machen

| Bereich | Funktionen |
| --- | --- |
| **Chats und Projekte** | Gespräche unter Projektordnern sammeln, Ordner auf- und zuklappen und wichtige Chats oder Projekte anpinnen. |
| **Chat und Arbeit** | Fragen besprechen oder einen Auftrag mit Planung, Umsetzung und anschließender Kontrolle bearbeiten lassen. |
| **App-Entwürfe** | Oberflächen mit Menüs, verschiedenen Ansichten und Dialogen erstellen und direkt ausprobieren. Die Vorschau lässt sich auch im Browser öffnen. |
| **Bilder** | Kostenlose Bildmodelle herunterladen und Bilder mit GPU oder CPU direkt auf dem Rechner erzeugen. |
| **Dateien** | Dateien an Gespräche anhängen, in der Mediathek verwalten und erstellte Dokumente oder Projektdateien speichern. |
| **Archiv** | Chats und Projekte ausblenden und später wiederherstellen. Dauerhaftes Löschen wird vorher bestätigt. |
| **Eigene Speicherorte** | Ordner für Chats, Dateien, Projekte, Modelle und Cache selbst festlegen. |

Seitenleiste, Gespräch und Vorschau lassen sich in der Breite verschieben. Während eines Auftrags zeigt die App die aktuelle Arbeitsphase an.

## Neu in 0.4.6

- **Bild erstellen** in der Seitenleiste: ein Motiv beschreiben und direkt auf dem Rechner erzeugen lassen.
- SDXL 1.0 und Stable Diffusion 1.5 unter **Einstellungen → Bilder** auswählen und kostenlos herunterladen.
- Eigene Speicherorte für Bildmodelle und fertige Bilder; Downloads lassen sich anhalten und fortsetzen.
- Automatische Beschleunigung, GPU über Vulkan oder Nur CPU unabhängig vom Sprachmodell wählen.
- Fertige Bilder im Chat und in der Arbeitsfläche ansehen, speichern oder im Browser öffnen. Stopp beendet die Bilderzeugung.

![Lokal mit SDXL erzeugtes Bild in OwnLLM](assets/screenshots/ownllm-bilderzeugung.png)

Die Modelle haben eigene Lizenzen, die bei der Auswahl verlinkt sind. Nach dem Download funktioniert die Bilderzeugung ohne Internetverbindung oder Konto bei einem Bilddienst.

[Ausführlicher Changelog](CHANGELOG.md)

## Installation und erster Start

1. Den Windows-Installer herunterladen und öffnen.
2. Den Programmordner wählen. Unter **Alle Speicherorte** kannst du die Datenordner einzeln festlegen.
3. Bei Bedarf ein lokales Modell einrichten und die Desktopverknüpfung auswählen.
4. **OwnLLM starten** anklicken und ein Projekt oder einen neuen Chat anlegen.

Das Sprachmodell benötigt zusätzlichen Speicherplatz. Die Qualität und Geschwindigkeit der Antworten hängen vom Modell und deinem Rechner ab. Für die Live-Vorschau wird [Microsoft Edge WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) benötigt.

## Updates

Unter **Einstellungen → Updates** kannst du nach einer neuen Version suchen, sie herunterladen und mit **Installieren und neu starten** übernehmen. Dafür brauchst du kein GitHub-Konto. Die gewählten Speicherorte sowie vorhandene Chats, Projekte und Modelle bleiben erhalten.

Bei einem manuellen Update OwnLLM zuerst über das Symbol im Infobereich beenden und den neuen Installer mit dem bisherigen Programmordner ausführen.

## Hinweise zur aktuellen Version

OwnLLM Studio befindet sich noch in Entwicklung. Der Windows-Installer ist derzeit nicht digital signiert.

Beim Löschen eines Chats bleiben seine Dateien im Projekt erhalten. Beim Entfernen eines Projekts werden dessen Chats und Mediathek-Einträge gelöscht; die Dateien bleiben in ihren bisherigen Ordnern auf dem Rechner.

## Fragen oder Fehler?

[Fehler melden](https://github.com/ZUMBYTE-AppSolution/ownllm-release/issues) · [Alle Downloads](https://github.com/ZUMBYTE-AppSolution/ownllm-release/releases) · [Zumbyte – AppSolution](https://www.zumbyte.de)

Nenne bei einem Fehler bitte die verwendete Version und die Schritte, bei denen er auftritt.

© 2026 Zumbyte AppSolution · [Impressum](https://www.zumbyte.de/impressum/) · [Datenschutz auf zumbyte.de](https://www.zumbyte.de/datenschutz/)
