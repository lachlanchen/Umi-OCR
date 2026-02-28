[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


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
  <a href="https://hosted.weblate.org/engage/umi-ocr/">
    <img src="https://hosted.weblate.org/widget/umi-ocr/svg-badge.svg" alt="translation status">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%207%2B%20%7C%20Linux%20x64-2ea44f?style=flat-square" alt="platform">
  <img src="https://img.shields.io/badge/OCR-Offline-1f6feb?style=flat-square" alt="offline OCR">
  <img src="https://img.shields.io/badge/Interface-GUI%20%7C%20CLI%20%7C%20HTTP-f97316?style=flat-square" alt="interfaces">
</p>

<div align="center">
  <h3>
    <a href="#table-of-contents">使用說明</a>
    <span> • </span>
    <a href="#download-releases">下載發行版</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">更新日誌</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">問題反饋</a>
  </h3>
</div>

<div align="center">
  <strong>免費、開源、支援批處理的離線 OCR 軟件</strong><br>
  <sub>相容 Windows 7 x64 與 Linux x64</sub>
</div>

## 概覽

Umi-OCR 是一款以桌面端為核心的 OCR 工具，重點面向離線處理、高吞吐批量工作流，以及實用的集成能力。

- **免費**：全部程式碼開源，永久免費使用。
- **便捷**：解壓即用，核心 OCR 不依賴網絡。
- **高效**：內建離線 OCR 引擎，支援多語言識別。
- **靈活**：支援 GUI 工作流、命令行控制與 HTTP API。
- **功能豐富**：支援截圖 OCR、批量 OCR、文件 OCR、二維碼識別/生成、公式識別入口。

| ✅ 快速信息 | 詳情 |
| --- | --- |
| 🧩 許可證 | MIT |
| 🌐 網絡要求 | 核心 OCR 工作流無需聯網 |
| 💻 平台 | Windows 7 x64+ / Linux x64 |
| 🛠 使用模式 | GUI、CLI、HTTP API |
| 🌍 翻譯 | 基於 Weblate 的社區本地化 |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

<a id="table-of-contents"></a>

## 目錄

- [功能特性](#features)
- [專案結構](#project-structure)
- [前置條件](#prerequisites)
- [安裝](#installation)
- [下載發行版](#download-releases)
- [使用](#usage)
- [設定](#configuration)
- [範例](#examples)
- [API 參考](#api-references)
- [開發說明](#development-notes)
- [故障排查](#troubleshooting)
- [本地化](#localization)
- [路線圖](#roadmap)
- [貢獻](#contribution)
- [支援](#support)
- [許可證](#license)

<a id="features"></a>

## 功能特性

### 截圖 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- 打開截圖 OCR 標籤頁後，可透過截圖快捷鍵觸發 OCR。
- 左側面板支援在圖片預覽中直接選取文字。
- 右側面板支援可編輯識別歷史及多條記錄複製。
- 支援貼上來自剪貼板的圖片。
- 公式識別參考：[Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### 文字後處理（版面解析）

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

內建方案可對 OCR 文字塊重排，提升可讀性：

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation`（適合程式碼片段）
- `No post-processing`（原始 OCR 輸出）

若所選 OCR 引擎模型支援，這些方案可處理橫排與直排（從右到左）版式。

### 批量 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 輸入格式：`jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 輸出格式：`txt, jsonl, md, csv(Excel)`
- 支援截圖 OCR 的文字後處理規則。
- 在 UI 工作流中基本沒有實際任務數量上限（單次支援數百張圖片）。
- 支援任務完成後自動關機/睡眠。
- 對超大圖片，請調整 `OCR settings -> image side limit`。

#### 忽略區域

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- 在批量 OCR 時排除固定水印/Logo 文字。
- 在忽略區域編輯器中，可用鼠標右鍵繪制多個矩形。
- 建議繪制略大於目標水印區域的矩形，以提高魯棒性。
- 忽略邏輯以文字塊為單位（區域內文字塊會被忽略）。

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 文件 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 輸入格式：`pdf, xps, epub, mobi, fb2, cbz`
- 有內嵌文字時優先提取，否則對掃描頁執行 OCR。
- 可導出可搜索的分層 PDF。
- 支援忽略區域（適用於頁眉/頁腳）。
- 支援任務完成後自動關機/睡眠。

### 二維碼

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

讀取模式：

- 支援截圖、貼上或拖拽本地圖片進行解碼。
- 支援單圖多碼識別。
- 支援 19 種格式：

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

生成模式：

- 可將文字生成二維碼/條形碼圖片。
- 支援格式選擇與糾錯等級設定。

### 全域設定

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- 添加快捷鍵並設定啟動行為。
- 切換介面語言。
- 切換主題（淺色/深色變體）。
- 設定字體與 UI 縮放。
- 切換 OCR 插件。
- 當 GPU 加速導致閃爍或介面錯位時，可切換渲染器（`Interface and Appearance -> Renderer`）。

<a id="project-structure"></a>

## 專案結構

### 倉庫關係

- [主倉庫](https://github.com/hiroi-sora/Umi-OCR)
- [插件倉庫](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows 運行時倉庫](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 運行時倉庫](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### 運行時目錄結構（上游規範佈局）

`**` 表示內容包含在當前主倉庫中。

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

### 當前倉庫快照的源碼樹

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

<a id="prerequisites"></a>

## 前置條件

### 終端用戶

| 專案 | 要求 |
| --- | --- |
| 操作系統 | Windows 7 x64+ 或 Linux x64 |
| CPU（推薦） | 支援 AVX 的 x64 CPU（用於基於 PaddleOCR 的插件） |
| 運行時（Windows 推薦） | 用於相容性的 Visual C++ 運行庫 |

### 開發者

- 請先閱讀並遵循以下平台運行時環境設定：
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- 本倉庫不提供可直接用於 pip 安裝的獨立 `requirements.txt` 或 `pyproject.toml`。

<a id="installation"></a>

## 安裝

### 方案 A：便攜發行包（推薦）

1. 下載 `.7z` 或自解壓 `.7z.exe` 包。
2. 解壓文件。
3. 啟動 `Umi-OCR.exe`。

### 方案 B：Scoop（Windows）

```bash
scoop bucket add extras
```

RapidOCR 變體（相容性更好）：

```bash
scoop install extras/umi-ocr
```

PaddleOCR 變體（速度略快）：

```bash
scoop install extras/umi-ocr-paddle
```

請勿同時安裝兩個變體（可能發生快捷方式衝突）。如有需要，請透過插件切換。

### 方案 C：透過運行時倉庫構建/運行

請按照以下倉庫的構建/運行時引導說明操作：

- [Windows 運行時設定](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 運行時設定](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="download-releases"></a>

## 下載發行版

| 鏡像 | 鏈接 | 說明 |
| --- | --- | --- |
| 藍奏雲 | https://hiroi-sora.lanzoul.com/s/umi-ocr | 區域鏡像 |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | 上游主發行頁面 |
| SourceForge | https://sourceforge.net/projects/umi-ocr | 備用下載鏡像 |

<a id="usage"></a>

## 使用

### 快速開始

- Umi-OCR 為便攜版，無需安裝程式。
- 解壓後啟動 `Umi-OCR.exe`。
- 若啟動失敗，請查看[故障排查](#troubleshooting)。

### 介面語言

首次啟動時，介面語言會根據系統區域自動選擇。

手動切換路徑：`Global Settings -> Language`。

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### 標籤頁與工作流

- 僅打開當前工作流所需的標籤頁。
- 可在標籤欄左上角切換視窗置頂。
- 可在右上角鎖定標籤頁，防止誤關閉。

### 命令行用法

CLI 手冊：[docs/README_CLI.md](docs/README_CLI.md)

基礎控制：

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

OCR 命令：

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

固定區域截圖：

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

二維碼命令：

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

輸出選項：

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### HTTP API 用法

HTTP 文件：[docs/http/README.md](docs/http/README.md)

關鍵端點：

| Endpoint | 用途 |
| --- | --- |
| `/api/ocr/get_options` | OCR 選項 |
| `/api/ocr` | 執行 OCR |
| `/api/doc/*` | 文件選項/上傳/結果/下載 |
| `/api/qrcode` | 二維碼解碼 |
| `/argv` | 透過 HTTP 調用 CLI 橋接 |

注意：在 `Global Settings` 中需保持 HTTP 服務開啟（預設開啟）。除非需要區域網路訪問，否則建議僅使用本地監聽地址。

<a id="configuration"></a>

## 設定

- 運行時設定保存在 `UmiOCR-data/.settings`（INI 格式）。
- 手動編輯設定後，可透過以下命令應用變更：

```bash
umi-ocr --reload
```

- 某些啟動/運行時相容狀態也可能涉及：
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/`（含運行時日誌的版本）

<a id="examples"></a>

## 範例

### 範例 1：按路徑批量 OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 範例 2：從多個路徑讀取二維碼

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 範例 3：指定尺寸生成二維碼

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### 範例 4：高級模組調用

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二維碼/1111.png","D:/Pictures/Screenshots/test/二維碼/2222.png"]'
```

<a id="api-references"></a>

## API 參考

- 命令行手冊：[docs/README_CLI.md](docs/README_CLI.md)
- HTTP API 手冊：[docs/http/README.md](docs/http/README.md)
- OCR API：[docs/http/api_ocr.md](docs/http/api_ocr.md)
- 文件 API：[docs/http/api_doc.md](docs/http/api_doc.md)
- 二維碼 API：[docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv 橋接：[docs/http/argv.md](docs/http/argv.md)

<a id="development-notes"></a>

## 開發說明

- 入口點：
  - `UmiOCR-data/main.py`（運行時引導）
  - `UmiOCR-data/py_src/run.py`（應用啟動）
- UI 技術棧：PySide2 + QML（`UmiOCR-data/qt_res/qml`）。
- 核心服務：
  - `py_src/server/*` 用於 HTTP 與命令傳輸
  - `py_src/mission/*` 用於隊列化 OCR/文件/二維碼任務
  - `py_src/ocr/*` 用於 OCR 後處理與輸出
- 生態支援的 OCR 引擎：
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- 運行時框架：[PyStand（客製版）](https://github.com/skywind3000/PyStand)

<a id="troubleshooting"></a>

## 故障排查

完整排障說明： https://github.com/hiroi-sora/Umi-OCR/issues/447

快速索引：

| 症狀 | 跳轉 |
| --- | --- |
| 找不到 `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL 上下文建立失敗 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 程式啟動即崩潰 | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 初始化失敗 | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| 缺少 `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- 安裝 VC 運行庫：https://aka.ms/vs/17/release/vc_redist.x64.exe
- 或使用備用啟動方式 `UmiOCR-data/RUN_GUI.bat`。
- 注意：`.bat` 啟動方式有局限（不支援 CLI 控制、快捷鍵自動化能力有限）。

### `Failed to create OpenGL context`

- 下載運行時補丁：https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 將解壓後的 DLL 放到 `UmiOCR-data/site-packages/PySide2/`。

### `Umi-OCR.exe has stopped working`

- 常見於在不同 Windows 版本間重用設定後。
- 刪除 `UmiOCR-data/.pre_settings` 後重試。

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- 通常是 CPU 不支援 AVX。
- 請使用 RapidOCR 變體，或切換為非 PaddleOCR 插件：
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- 常見於未打補丁的早期 Windows 7（尤其缺少 `KB2533623`）。
- 建議修復：運行完整 Windows Update 並重啟。

### Crash while exporting searchable PDF

- 常由 Windows 7 缺少更新導致（尤其 `KB4534310` 及其依賴）。
- 建議修復：透過 Windows Update 安裝所有缺失的系統更新。

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- 安裝 VC 運行庫：https://aka.ms/vs/17/release/vc_redist.x64.exe

### 手動放置快捷方式

若自動建立快捷方式失敗，可手動放置：

- 開始選單：`C:\ProgramData\Microsoft\Windows\Start Menu`
- 啟動項：`C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

<a id="localization"></a>

## 本地化

本專案使用 Weblate 進行協作翻譯：

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

本倉庫中的 README 多語言文件：

| 語言 | 文件 |
| --- | --- |

感謝所有翻譯貢獻者：

| 翻譯者 | 貢獻語言 |
| --- | --- |
| [楊鵬](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

如果有錯誤或遺漏，歡迎在[此討論](https://github.com/hiroi-sora/Umi-OCR/discussions/449)回覆。

<a id="roadmap"></a>

## 路線圖

### 已完成

- 標籤頁架構。
- OCR API 控制器。
- OCR mission/task 控制器。
- 支援淺色/深色的主題管理器。
- 批量 OCR。
- 截圖 OCR。
- 熱鍵機制。
- 系統托盤選單。
- 文字塊後處理（佈局優化）。
- 引擎內存清理。
- 多語言介面。
- 命令行模式。
- Windows 7 相容。
- Excel（CSV）輸出格式。
- 截圖時支援 `Esc` 中斷。
- 外部主題文件。
- 字體切換。
- 加載動畫。
- 忽略區域。
- 二維碼識別。
- 批量識別中的圖片預覽。
- PDF 識別。
- 使用本地圖片查看器打開圖像。[#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- 重復上一次截圖區域。[#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- 修復文件識別在 Windows 7 下的相容性問題。
- HTTP 與 CLI 接口支援二維碼讀取/生成。（#423）
- 二維碼接口文件。
- Linux 平台遷移。
- HTTP 文件識別 API。

### 長期計劃

以下條目為規劃中的想法，可能在開發過程中調整：

- [ ] 重構底層插件機制。
- [ ] 在線 OCR API 插件。
- [ ] 獨立的公式識別插件。
- [ ] 專用公式標籤頁與 LaTeX 渲染。
- [ ] 更新檢測機制。
- [ ] 除版面解析外的更多後處理模組。
- [ ] 關鍵介面功能的事件觸發器。
- [ ] 基於 GPU 的離線 OCR。
- [ ] 圖片翻譯。
- [ ] 離線翻譯。
- [ ] 固定區域 OCR。
- [ ] 表格識別並導出為 Excel。
- [ ] 歷史記錄系統。
- [ ] 擴展到 macOS/Ubuntu 等平台的相容性。

<a id="contribution"></a>

## 貢獻

歡迎貢獻。

- 透過 [Issues](https://github.com/hiroi-sora/Umi-OCR/issues) 提交錯誤或功能請求。
- 在 [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) 參與方案討論。
- 透過 [Weblate](https://hosted.weblate.org/engage/umi-ocr/) 貢獻翻譯。
- 涉及引擎/插件開發，也請參考 [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)。

開發環境搭建請遵循以下平台運行時倉庫：

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="support"></a>

## 支援

Umi-OCR 主要由 [hiroi-sora](https://github.com/hiroi-sora) 在業餘時間維護與開發。

如果這個專案對你有幫助，歡迎贊助支援：

- 愛發電（中國）：https://afdian.com/a/hiroi-sora

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

<a id="license"></a>

## 許可證

本專案採用 MIT 許可證。

- [LICENSE](LICENSE)
