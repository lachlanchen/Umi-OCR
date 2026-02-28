[English](README.md) · [العربية](i18n/README.ar.md) · [Español](i18n/README.es.md) · [Français](i18n/README.fr.md) · [日本語](i18n/README.ja.md) · [한국어](i18n/README.ko.md) · [Tiếng Việt](i18n/README.vi.md) · [中文 (简体)](i18n/README.zh-Hans.md) · [中文（繁體）](i18n/README.zh-Hant.md) · [Deutsch](i18n/README.de.md) · [Русский](i18n/README.ru.md)


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
  <strong>Free, open-source, batch offline OCR software</strong><br>
  <sub>Compatible with Windows 7 x64 and Linux x64</sub>
</div>

### 🚀 At a Glance

| Focus | Details |
| --- | --- |
| 📦 Distribution | Portable desktop app (`.7z` and `.7z.exe`) |
| 🧠 Core Mode | Offline batch OCR with screenshot, document, and QR workflows |
| 🧩 Interfaces | GUI, CLI, and HTTP API |
| 🌐 Localization | Community translated via Weblate |

---

## Overview

Umi-OCR is a desktop-first OCR tool focused on offline processing, high throughput batch workflows, and practical integrations.

- **Free**: All code is open source and free to use.
- **Convenient**: Extract and run locally, no network dependency for core OCR.
- **Efficient**: Bundled offline OCR engines with multi-language support.
- **Flexible**: Supports GUI workflows, command line control, and HTTP APIs.
- **Feature-rich**: Screenshot OCR, batch OCR, document OCR, QR code read/create, formula recognition entry point.

| ✅ Quick Facts | Details |
| --- | --- |
| 🧩 License | MIT |
| 🌐 Network Requirement | No network needed for core OCR workflows |
| 💻 Platform | Windows 7 x64+ / Linux x64 |
| 🛠 Usage Modes | GUI, CLI, HTTP API |
| 🌍 Translation | Weblate-based community localization |

### Built for Practical Workflows

| Workflow | Core Capability |
| --- | --- |
| Screenshot processing | Crop, select, and transcribe directly from live captures |
| Batch handling | Process folders, tune post-processing, and export structured text outputs |
| Document OCR | OCR scanned documents and produce searchable layered PDFs |
| QR operations | Decode multiple codes and generate custom QR/barcode assets |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## Table of Contents

- [✨ Features](#features)
- [🧱 Project Structure](#project-structure)
- [🧰 Prerequisites](#prerequisites)
- [⚙️ Installation](#installation)
- [⬇️ Download Releases](#download-releases)
- [🧪 Usage](#usage)
- [🔧 Configuration](#configuration)
- [🧩 Examples](#examples)
- [📡 API References](#api-references)
- [🧠 Development Notes](#development-notes)
- [🛠️ Troubleshooting](#troubleshooting)
- [🌐 Localization](#localization)
- [🗺️ Roadmap](#roadmap)
- [🤝 Contribution](#contribution)
- [❤️ Support](#support)
- [📜 License](#license)

## Features

### Screenshot OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- Trigger OCR by screenshot shortcut after opening the Screenshot OCR tab.
- Left panel supports text selection directly in image preview.
- Right panel supports editable recognition history and multi-record copy.
- Supports pasted images from clipboard.
- Formula recognition reference: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### Text Post-Processing (Layout Parsing)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

Built-in schemes to reorder OCR blocks and improve readability:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (useful for code snippets)
- `No post-processing` (raw OCR output)

These schemes can handle horizontal and vertical (right-to-left) layout if the selected OCR engine model supports it.

### Batch OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- Input formats: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- Output formats: `txt, jsonl, md, csv(Excel)`
- Supports text post-processing rules from Screenshot OCR.
- No practical task-count cap in UI workflow (hundreds of images per run are supported).
- Supports auto shutdown/sleep after task completion.
- For extra-large images, adjust `OCR settings -> image side limit`.

#### Ignore Regions

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- Exclude stable watermark/logo text during batch OCR.
- Draw multiple rectangles with right mouse button in the Ignore Region editor.
- Draw rectangles larger than the target watermark area for better robustness.
- The ignore behavior is block-based (text block inside region is ignored).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### Document OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- Input formats: `pdf, xps, epub, mobi, fb2, cbz`
- Extract embedded text when available or OCR scanned pages.
- Export searchable layered PDFs.
- Supports ignore regions (for headers/footers).
- Supports auto shutdown/sleep after task completion.

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

Read mode:

- Screenshot, paste, or drag local images for decoding.
- Supports multiple codes in one image.
- Supports 19 formats:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

Generate mode:

- Generate QR/barcode images from text.
- Supports format selection and error-correction settings.

### Global Settings

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- Add shortcuts and configure startup behavior.
- Switch UI language.
- Switch themes (light/dark variants).
- Configure font and UI scaling.
- Switch OCR plugins.
- Change renderer (`Interface and Appearance -> Renderer`) when GPU acceleration causes flicker or UI offset.

## Project Structure

### Repository Relations

- [Main repository](https://github.com/hiroi-sora/Umi-OCR)
- [Plugin repository](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows runtime repository](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime repository](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### Runtime Layout (Canonical Upstream Layout)

`**` means content included in this main repository.

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
| Operating System | Windows 7 x64+ or Linux x64 |
| CPU (Recommended) | x64 CPU with AVX support (for PaddleOCR-based plugins) |
| Runtime (Windows Recommended) | Visual C++ runtime for compatibility |

### Developers

- Read and follow platform runtime setup from:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- This repository does not provide a standalone `requirements.txt` or `pyproject.toml` for direct pip-based setup.

## Installation

### Option A: Portable Release Package (Recommended)

1. Download `.7z` or self-extracting `.7z.exe` package.
2. Extract files.
3. Launch `Umi-OCR.exe`.

### Option B: Scoop (Windows)

```bash
scoop bucket add extras
```

RapidOCR variant (better compatibility):

```bash
scoop install extras/umi-ocr
```

PaddleOCR variant (slightly faster):

```bash
scoop install extras/umi-ocr-paddle
```

Do not install both variants simultaneously (shortcut conflicts may occur). Use plugin switching if needed.

### Option C: Build/Run via Runtime Repositories

Follow build/runtime bootstrap instructions from:

- [Windows runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Download Releases

| Mirror | Link | Notes |
| --- | --- | --- |
| Lanzou | [Regional mirror](https://hiroi-sora.lanzoul.com/s/umi-ocr) | China-friendly mirror |
| GitHub | [Latest releases](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | Primary upstream release page |
| SourceForge | [Download mirror](https://sourceforge.net/projects/umi-ocr) | Legacy alternate channel |

## Usage

### Getting Started

- Umi-OCR is portable; no installer is required.
- Launch `Umi-OCR.exe` after extraction.
- If startup fails, see [Troubleshooting](#troubleshooting).

### Interface Language

On first launch, UI language is auto-selected by system locale.

For manual switching: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### Tabs and Workflow

- Open only required tabs for your workflow.
- Toggle always-on-top from the top-left corner of tab bar.
- Lock tabs from top-right to prevent accidental close.

### Command-Line Usage

CLI manual: [docs/README_CLI.md](docs/README_CLI.md)

Basic controls:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

OCR commands:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

Screenshot with fixed region:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

QR commands:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

Output options:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### HTTP API Usage

HTTP docs: [docs/http/README.md](docs/http/README.md)

Key endpoints:

| Endpoint | Purpose |
| --- | --- |
| `/api/ocr/get_options` | OCR options |
| `/api/ocr` | Execute OCR |
| `/api/doc/*` | Document options/upload/result/download |
| `/api/qrcode` | QR decode |
| `/argv` | CLI bridge over HTTP |

Note: In `Global Settings`, HTTP service must remain enabled (default). Use local-only host unless LAN access is required.

## Configuration

- Runtime settings are stored in `UmiOCR-data/.settings` (INI format).
- After editing config manually, apply changes with:

```bash
umi-ocr --reload
```

- Some startup/runtime compatibility state may also involve:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (for versions with runtime logging)

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

- Command line manual: [docs/README_CLI.md](docs/README_CLI.md)
- HTTP API manual: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- Document API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv bridge: [docs/http/argv.md](docs/http/argv.md)

## Development Notes

- Entry points:
  - `UmiOCR-data/main.py` (runtime bootstrap)
  - `UmiOCR-data/py_src/run.py` (application startup)
- UI stack: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- Core services:
  - `py_src/server/*` for HTTP + command transport
  - `py_src/mission/*` for queued OCR/Doc/QR tasks
  - `py_src/ocr/*` for OCR post-processing and outputs
- OCR engines supported by ecosystem:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- Runtime framework: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## Troubleshooting

For full troubleshooting details: [https://github.com/hiroi-sora/Umi-OCR/issues/447](https://github.com/hiroi-sora/Umi-OCR/issues/447)

Quick index:

| Symptom | Jump |
| --- | --- |
| Cannot find `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL context creation failed | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| App crashes on start | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR init failure | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| Missing `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- Install VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe
- Or launch with fallback `UmiOCR-data/RUN_GUI.bat`.
- Note: `.bat` launcher has limitations (no CLI control, limited shortcut automation).

### `Failed to create OpenGL context`

- Download runtime patch: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- Put extracted DLL into `UmiOCR-data/site-packages/PySide2/`.

### `Umi-OCR.exe has stopped working`

- Common after reusing config across different Windows versions.
- Remove `UmiOCR-data/.pre_settings` and retry.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- Likely CPU lacks AVX.
- Use RapidOCR variant or switch away from PaddleOCR plugin:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- Common on unpatched early Windows 7 (especially missing `KB2533623`).
- Recommended fix: run full Windows Update and reboot.

### Crash while exporting searchable PDF

- Often caused by missing Windows 7 updates (especially `KB4534310` and dependencies).
- Recommended fix: install all missing system updates via Windows Update.

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- Install VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe

### Manual Shortcut Placement

If auto shortcut creation fails, place shortcuts manually:

- Start menu: `C:\ProgramData\Microsoft\Windows\Start Menu`
- Startup: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## Localization

This project uses Weblate for collaborative localization:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

README language files in this repository:

| Language | File |
| --- | --- |

Thanks to all translators:

| Translator | Contributed Languages |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

If there are mistakes or omissions, please reply in [this discussion](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

## Roadmap

### Completed

- Tab-page architecture.
- OCR API controller.
- OCR mission/task controller.
- Theme manager with light/dark support.
- Batch OCR.
- Screenshot OCR.
- Hotkey mechanism.
- System tray menu.
- Text block post-processing (layout optimization).
- Engine memory cleanup.
- Multi-language UI.
- Command-line mode.
- Windows 7 compatibility.
- Excel (CSV) output format.
- `Esc` interrupt for screenshot.
- External theme files.
- Font switching.
- Loading animation.
- Ignore regions.
- QR code recognition.
- Image preview in batch recognition.
- PDF recognition.
- Open image with local image viewer. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- Repeat previous screenshot region. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- Fixed Windows 7 compatibility issue in document recognition.
- QR read/create support in HTTP and CLI interfaces. (#423)
- QR interface documentation.
- Linux platform migration.
- HTTP document-recognition API.

### Long-Term Plans

The following items are planned ideas and may evolve during development:

- [ ] Refactor underlying plugin mechanism.
- [ ] Online OCR API plugin.
- [ ] Independent formula-recognition plugin.
- [ ] Dedicated formula tab with LaTeX rendering.
- [ ] Update-check mechanism.
- [ ] Additional post-processing modules beyond layout parsing.
- [ ] Event triggers for key interface functions.
- [ ] GPU-based offline OCR.
- [ ] Image translation.
- [ ] Offline translation.
- [ ] Fixed-region OCR.
- [ ] Table recognition to Excel output.
- [ ] History system.
- [ ] Compatibility expansion for platforms such as macOS/Ubuntu.

## Contribution

Contributions are welcome.

- Report bugs or request features via [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- Discuss ideas in [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- Contribute translations via [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- For engine/plugin work, also see [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

For development setup, follow platform runtime repositories:

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

This project is licensed under the MIT License.

- [LICENSE](LICENSE)
