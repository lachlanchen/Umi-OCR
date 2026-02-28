[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)



[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)


<p align="center">
  <a href="https://github.com/hiroi-sora/Umi-OCR">
    <img width="200" height="128" src="https://tupian.li/images/2022/10/27/icon---256.png" alt="Umi-OCR">
  </a>
</p>

<h1 align="center">Umi-OCR</h1>

<p align="center">
  <a href="https://github.com/hiroi-sora/Umi-OCR/releases/latest">
    <img src="https://img.shields.io/github/v/release/hiroi-sora/Umi-OCR?style=flat-square" alt="Umi-OCR">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/hiroi-sora/Umi-OCR?style=flat-square" alt="LICENSE">
  </a>
  <a href="#download-releases">
    <img src="https://img.shields.io/github/downloads/hiroi-sora/Umi-OCR/total?style=flat-square" alt="downloads">
  </a>
  <a href="https://star-history.com/#hiroi-sora/Umi-OCR">
    <img src="https://img.shields.io/github/stars/hiroi-sora/Umi-OCR?style=flat-square" alt="stars">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/forks">
    <img src="https://img.shields.io/github/forks/hiroi-sora/Umi-OCR?style=flat-square" alt="forks">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/issues">
    <img src="https://img.shields.io/github/issues-raw/hiroi-sora/Umi-OCR?style=flat-square&color=d97706" alt="open issues">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/pulls">
    <img src="https://img.shields.io/github/issues-pr/hiroi-sora/Umi-OCR?style=flat-square&color=2ea44f" alt="open pull requests">
  </a>
  <a href="https://hosted.weblate.org/engage/umi-ocr/">
    <img src="https://hosted.weblate.org/widget/umi-ocr/svg-badge.svg" alt="translation status">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%207%2B%20%7C%20Linux%20x64-2ea44f?style=flat-square" alt="platform">
  <img src="https://img.shields.io/badge/OCR-Offline-1f6feb?style=flat-square" alt="offline OCR">
  <img src="https://img.shields.io/badge/Interface-GUI%20%7C%20CLI%20%7C%20HTTP-f97316?style=flat-square" alt="interfaces">
  <img src="https://img.shields.io/github/last-commit/hiroi-sora/Umi-OCR?style=flat-square" alt="last commit">
  <img src="https://img.shields.io/github/commit-activity/m/hiroi-sora/Umi-OCR?style=flat-square" alt="monthly commits">
</p>

<div align="center">
  <h3>
    <a href="#table-of-contents">Usage</a>
    <span> • </span>
    <a href="#download-releases">Download Releases</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">Changelog</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">Report Issues</a>
  </h3>
</div>

<div align="center">
  <strong>Kostenlose, quelloffene Batch-OCR-Software für Offline-Nutzung</strong><br>
  <sub>Kompatibel mit Windows 7 x64 und Linux x64</sub>
</div>

## Overview

Umi-OCR ist ein OCR-Tool mit Desktop-Fokus, das auf Offline-Verarbeitung, Batch-Workflows mit hohem Durchsatz und praxistaugliche Integrationen ausgelegt ist.

- **Kostenlos**: Der gesamte Code ist Open Source und frei nutzbar.
- **Praktisch**: Entpacken und lokal ausführen, keine Netzwerkabhängigkeit für Kern-OCR.
- **Effizient**: Enthält gebündelte Offline-OCR-Engines mit Mehrsprachenunterstützung.
- **Flexibel**: Unterstützt GUI-Workflows, Kommandozeilensteuerung und HTTP-APIs.
- **Funktionsreich**: Screenshot-OCR, Batch-OCR, Dokument-OCR, QR-Code lesen/erzeugen, Einstiegspunkt für Formel-Erkennung.

| ✅ Kurzfakten | Details |
| --- | --- |
| 🧩 Lizenz | MIT |
| 🌐 Netzwerk-Anforderung | Kein Netzwerk für zentrale OCR-Workflows erforderlich |
| 💻 Plattform | Windows 7 x64+ / Linux x64 |
| 🛠 Nutzungsmodi | GUI, CLI, HTTP API |
| 🌍 Übersetzung | Community-Lokalisierung über Weblate |

### Für praktische Workflows gemacht

| Workflow | Kern-Funktion |
| --- | --- |
| Screenshot-Verarbeitung | Zuschneiden, auswählen und direkt aus Live-Aufnahmen transkribieren |
| Batch-Verarbeitung | Ordner stapelweise verarbeiten, Nachbearbeitung anpassen und strukturierte Textergebnisse exportieren |
| Dokumenten-OCR | Gescannte Dokumente OCR-en und durchsuchbare PDFs mit Ebenen erzeugen |
| QR-Vorgänge | Mehrere Codes decodieren und individuelle QR-/Barcode-Dateien erstellen |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Download Releases](#download-releases)
- [Usage](#usage)
- [Configuration](#configuration)
- [Examples](#examples)
- [API References](#api-references)
- [Development Notes](#development-notes)
- [Troubleshooting](#troubleshooting)
- [Localization](#localization)
- [Roadmap](#roadmap)
- [Contribution](#contribution)
- [Support](#support)
- [License](#license)

## Features

### Screenshot OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- OCR per Screenshot-Shortcut auslösen, nachdem der Tab für Screenshot-OCR geöffnet wurde.
- Das linke Panel unterstützt direkte Textauswahl in der Bildvorschau.
- Das rechte Panel unterstützt bearbeitbaren Erkennungsverlauf und Kopieren mehrerer Einträge.
- Unterstützt eingefügte Bilder aus der Zwischenablage.
- Referenz zur Formel-Erkennung: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### Text Post-Processing (Layout Parsing)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

Integrierte Schemata zum Neuordnen von OCR-Blöcken und zur Verbesserung der Lesbarkeit:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (nützlich für Code-Snippets)
- `No post-processing` (rohe OCR-Ausgabe)

Diese Schemata können horizontale und vertikale (rechts-nach-links) Layouts verarbeiten, sofern das gewählte OCR-Engine-Modell dies unterstützt.

### Batch OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- Eingabeformate: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- Ausgabeformate: `txt, jsonl, md, csv(Excel)`
- Unterstützt Text-Nachverarbeitungsregeln aus Screenshot OCR.
- Kein praktisches Aufgabenlimit im UI-Workflow (Hunderte Bilder pro Durchlauf werden unterstützt).
- Unterstützt automatisches Herunterfahren/Energiesparen nach Abschluss der Aufgaben.
- Bei sehr großen Bildern `OCR settings -> image side limit` anpassen.

#### Ignore Regions

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- Schließt stabile Wasserzeichen-/Logo-Texte während Batch-OCR aus.
- Im Ignore-Region-Editor mehrere Rechtecke mit der rechten Maustaste zeichnen.
- Rechtecke für bessere Robustheit größer als den eigentlichen Wasserzeichenbereich zeichnen.
- Das Ignorieren arbeitet blockbasiert (Textblock innerhalb der Region wird ignoriert).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### Document OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- Eingabeformate: `pdf, xps, epub, mobi, fb2, cbz`
- Extrahiert eingebetteten Text, wenn vorhanden, oder führt OCR auf gescannten Seiten aus.
- Exportiert durchsuchbare PDFs mit Textebene.
- Unterstützt Ignore-Regions (für Kopf-/Fußzeilen).
- Unterstützt automatisches Herunterfahren/Energiesparen nach Abschluss der Aufgaben.

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

Lesemodus:

- Screenshot erstellen, Bild einfügen oder lokale Bilder zum Dekodieren per Drag-and-Drop laden.
- Unterstützt mehrere Codes in einem Bild.
- Unterstützt 19 Formate:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

Erzeugungsmodus:

- Erstellt QR-/Barcode-Bilder aus Text.
- Unterstützt Formatauswahl und Fehlerkorrektur-Einstellungen.

### Global Settings

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- Verknüpfungen hinzufügen und Startverhalten konfigurieren.
- UI-Sprache wechseln.
- Themes wechseln (helle/dunkle Varianten).
- Schriftart und UI-Skalierung konfigurieren.
- OCR-Plugins wechseln.
- Renderer ändern (`Interface and Appearance -> Renderer`), wenn GPU-Beschleunigung Flackern oder UI-Versatz verursacht.

## Project Structure

### Repository Relations

- [Main repository](https://github.com/hiroi-sora/Umi-OCR)
- [Plugin repository](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows runtime repository](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime repository](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### Runtime Layout (Canonical Upstream Layout)

`**` bedeutet Inhalt, der in diesem Haupt-Repository enthalten ist.

```text
Umi-OCR
├─ Umi-OCR.exe
├─ umi-ocr.sh
└─ UmiOCR-data
   ├─ main.py **
   ├─ version.py **
   ├─ qt_res **
   │  └─ Qt resources, including icons and QML source
   ├─ py_src **
   │  └─ Python source
   ├─ plugins
   │  └─ OCR plugins
   └─ i18n **
      └─ translation files
```

### Source Tree in This Repository Snapshot

```text
.
├── README.md
├── README_en.md
├── README_ja.md
├── CHANGE_LOG.md
├── LICENSE
├── docs/
│   ├── README_CLI.md
│   └── http/
├── UmiOCR-data/
│   ├── main.py
│   ├── py_src/
│   │   ├── run.py
│   │   ├── server/
│   │   ├── mission/
│   │   ├── ocr/
│   │   ├── tag_pages/
│   │   ├── plugins_controller/
│   │   ├── image_controller/
│   │   └── utils/
│   ├── qt_res/
│   │   ├── qml/
│   │   └── images/
│   └── i18n/
├── dev-tools/
│   └── i18n/
└── i18n/
```

## Prerequisites

### End Users

| Item | Requirement |
| --- | --- |
| Operating System | Windows 7 x64+ oder Linux x64 |
| CPU (Recommended) | x64-CPU mit AVX-Unterstützung (für PaddleOCR-basierte Plugins) |
| Runtime (Windows Recommended) | Visual C++ Runtime für Kompatibilität |

### Developers

- Plattformabhängige Runtime-Einrichtung lesen und befolgen:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- Dieses Repository enthält kein eigenständiges `requirements.txt` oder `pyproject.toml` für direkte pip-basierte Einrichtung.

## Installation

### Option A: Portable Release-Pakete (Empfohlen)

1. `.7z`- oder selbstentpackendes `.7z.exe`-Paket herunterladen.
2. Dateien entpacken.
3. `Umi-OCR.exe` starten.

### Option B: Scoop (Windows)

```bash
scoop bucket add extras
```

RapidOCR-Variante (bessere Kompatibilität):

```bash
scoop install extras/umi-ocr
```

PaddleOCR-Variante (leicht schneller):

```bash
scoop install extras/umi-ocr-paddle
```

Nicht beide Varianten gleichzeitig installieren (es können Shortcut-Konflikte auftreten). Bei Bedarf Plugin-Umschaltung verwenden.

### Option C: Build/Run über Runtime-Repositories

Build-/Runtime-Bootstrap-Anleitungen hier folgen:

- [Windows runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Download Releases

| Mirror | Link | Notes |
| --- | --- | --- |
| Lanzou | https://hiroi-sora.lanzoul.com/s/umi-ocr | Regionaler Mirror |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | Primäre Upstream-Release-Seite |
| SourceForge | https://sourceforge.net/projects/umi-ocr | Alternativer Download-Mirror |

## Usage

### Getting Started

- Umi-OCR ist portabel; ein Installer ist nicht erforderlich.
- Nach dem Entpacken `Umi-OCR.exe` starten.
- Falls der Start fehlschlägt, siehe [Troubleshooting](#troubleshooting).

### Interface Language

Beim ersten Start wird die UI-Sprache automatisch anhand des Systemgebietsschemas ausgewählt.

Manuelles Umschalten: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### Tabs and Workflow

- Nur die für deinen Workflow benötigten Tabs öffnen.
- Always-on-top in der linken oberen Ecke der Tab-Leiste umschalten.
- Tabs oben rechts sperren, um versehentliches Schließen zu vermeiden.

### Command-Line Usage

CLI-Handbuch: [docs/README_CLI.md](docs/README_CLI.md)

Grundlegende Steuerbefehle:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

OCR-Befehle:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

Screenshot mit festem Bereich:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

QR-Befehle:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

Ausgabeoptionen:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### HTTP API Usage

HTTP-Dokumentation: [docs/http/README.md](docs/http/README.md)

Wichtige Endpunkte:

| Endpoint | Purpose |
| --- | --- |
| `/api/ocr/get_options` | OCR-Optionen |
| `/api/ocr` | OCR ausführen |
| `/api/doc/*` | Dokumentoptionen/Upload/Ergebnis/Download |
| `/api/qrcode` | QR dekodieren |
| `/argv` | CLI-Brücke über HTTP |

Hinweis: In `Global Settings` muss der HTTP-Dienst aktiviert bleiben (Standard). Verwende einen nur lokalen Host, außer LAN-Zugriff wird benötigt.

## Configuration

- Runtime-Einstellungen werden in `UmiOCR-data/.settings` gespeichert (INI-Format).
- Nach manueller Konfigurationsänderung mit folgendem Befehl anwenden:

```bash
umi-ocr --reload
```

- Einige Startup-/Runtime-Kompatibilitätszustände können außerdem betreffen:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (für Versionen mit Runtime-Logging)

## Examples

### Example 1: Batch OCR by Path

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### Example 2: Read QR from Multiple Paths

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### Example 3: Generate QR with Explicit Size

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### Example 4: Advanced Module Invocation

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## API References

- Kommandozeilen-Handbuch: [docs/README_CLI.md](docs/README_CLI.md)
- HTTP-API-Handbuch: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- Document API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv bridge: [docs/http/argv.md](docs/http/argv.md)

## Development Notes

- Einstiegspunkte:
  - `UmiOCR-data/main.py` (Runtime-Bootstrap)
  - `UmiOCR-data/py_src/run.py` (Anwendungsstart)
- UI-Stack: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- Kerndienste:
  - `py_src/server/*` für HTTP + Command-Transport
  - `py_src/mission/*` für Warteschlangenaufgaben von OCR/Dokument/QR
  - `py_src/ocr/*` für OCR-Nachverarbeitung und Ausgaben
- Vom Ökosystem unterstützte OCR-Engines:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- Runtime-Framework: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## Troubleshooting

Für vollständige Troubleshooting-Details: https://github.com/hiroi-sora/Umi-OCR/issues/447

Schnellindex:

| Symptom | Jump |
| --- | --- |
| Cannot find `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL context creation failed | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| App crashes on start | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR init failure | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| Missing `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- VC-Runtime installieren: https://aka.ms/vs/17/release/vc_redist.x64.exe
- Oder mit Fallback `UmiOCR-data/RUN_GUI.bat` starten.
- Hinweis: Der `.bat`-Launcher hat Einschränkungen (keine CLI-Steuerung, eingeschränkte Shortcut-Automatisierung).

### `Failed to create OpenGL context`

- Runtime-Patch herunterladen: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- Extrahierte DLL in `UmiOCR-data/site-packages/PySide2/` ablegen.

### `Umi-OCR.exe has stopped working`

- Häufig nach Wiederverwendung der Konfiguration über unterschiedliche Windows-Versionen hinweg.
- `UmiOCR-data/.pre_settings` entfernen und erneut versuchen.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- Wahrscheinlich unterstützt die CPU kein AVX.
- RapidOCR-Variante verwenden oder vom PaddleOCR-Plugin wegwechseln:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- Häufig bei ungepatchtem frühem Windows 7 (besonders bei fehlendem `KB2533623`).
- Empfohlene Lösung: Vollständiges Windows Update ausführen und neu starten.

### Crash while exporting searchable PDF

- Oft verursacht durch fehlende Windows-7-Updates (insbesondere `KB4534310` und Abhängigkeiten).
- Empfohlene Lösung: Alle fehlenden Systemupdates per Windows Update installieren.

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- VC-Runtime installieren: https://aka.ms/vs/17/release/vc_redist.x64.exe

### Manual Shortcut Placement

Falls die automatische Verknüpfungserstellung fehlschlägt, Verknüpfungen manuell platzieren:

- Startmenü: `C:\ProgramData\Microsoft\Windows\Start Menu`
- Autostart: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## Localization

Dieses Projekt nutzt Weblate für kollaborative Lokalisierung:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

README-Sprachdateien in diesem Repository:

| Language | File |
| --- | --- |

Danke an alle Übersetzerinnen und Übersetzer:

| Translator | Contributed Languages |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

Bei Fehlern oder Auslassungen antworte bitte in [dieser Diskussion](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

## Roadmap

### Completed

- Tab-Seiten-Architektur.
- OCR-API-Controller.
- OCR-Mission-/Task-Controller.
- Theme-Manager mit Hell-/Dunkel-Unterstützung.
- Batch OCR.
- Screenshot OCR.
- Hotkey-Mechanismus.
- System-Tray-Menü.
- Textblock-Nachverarbeitung (Layout-Optimierung).
- Engine-Speicherbereinigung.
- Mehrsprachige UI.
- Kommandozeilenmodus.
- Windows-7-Kompatibilität.
- Excel-(CSV)-Ausgabeformat.
- `Esc`-Unterbrechung für Screenshot.
- Externe Theme-Dateien.
- Schriftwechsel.
- Ladeanimation.
- Ignore Regions.
- QR-Code-Erkennung.
- Bildvorschau in Batch-Erkennung.
- PDF-Erkennung.
- Bild mit lokalem Bildbetrachter öffnen. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- Vorherigen Screenshot-Bereich wiederholen. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- Kompatibilitätsproblem der Dokumenterkennung unter Windows 7 behoben.
- Unterstützung für QR lesen/erzeugen in HTTP- und CLI-Schnittstellen. (#423)
- QR-Schnittstellen-Dokumentation.
- Linux-Plattform-Migration.
- HTTP-API für Dokumenterkennung.

### Long-Term Plans

Die folgenden Punkte sind geplante Ideen und können sich während der Entwicklung ändern:

- [ ] Zugrunde liegenden Plugin-Mechanismus refaktorieren.
- [ ] Online-OCR-API-Plugin.
- [ ] Eigenständiges Plugin für Formel-Erkennung.
- [ ] Eigener Formel-Tab mit LaTeX-Rendering.
- [ ] Mechanismus zur Update-Prüfung.
- [ ] Zusätzliche Nachverarbeitungsmodule über Layout-Parsing hinaus.
- [ ] Event-Trigger für zentrale Interface-Funktionen.
- [ ] GPU-basierte Offline-OCR.
- [ ] Bildübersetzung.
- [ ] Offline-Übersetzung.
- [ ] OCR mit festem Bereich.
- [ ] Tabellenerkennung mit Excel-Ausgabe.
- [ ] Verlaufssystem.
- [ ] Erweiterte Kompatibilität für Plattformen wie macOS/Ubuntu.

## Contribution

Beiträge sind willkommen.

- Fehler melden oder Funktionen anfragen über [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- Ideen in [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) diskutieren.
- Übersetzungen über [Weblate](https://hosted.weblate.org/engage/umi-ocr/) beitragen.
- Für Engine-/Plugin-Arbeiten siehe auch [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

Für das Entwicklungs-Setup den Plattform-Runtime-Repositories folgen:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

## License

Dieses Projekt ist unter der MIT License lizenziert.

- [LICENSE](LICENSE)
