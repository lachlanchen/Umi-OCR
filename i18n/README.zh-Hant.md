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
    <a href="#table-of-contents">使用方式</a>
    <span> • </span>
    <a href="#download-releases">下載發行版</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">更新日誌</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">問題回報</a>
  </h3>
</div>

<div align="center">
  <strong>免費、開源、支援批次作業的離線 OCR 軟體</strong><br>
  <sub>相容 Windows 7 x64 與 Linux x64</sub>
</div>

## 概覽

<a id="table-of-contents"></a>

Umi-OCR 是一款以桌面端為核心、以離線處理、高吞吐批次工作流與實務整合為重點的 OCR 工具。

- **免費**：所有程式碼皆開源且可自由使用。
- **便利**：可直接在本機解壓執行，核心 OCR 不依賴網路。
- **高效**：整合離線 OCR 引擎，提供多語系支援。
- **靈活**：支援 GUI 流程、命令列控制與 HTTP API。
- **功能豐富**：提供擷圖 OCR、批次 OCR、文件 OCR、QR Code 讀取/產生、公式辨識入口。

| ✅ 快速資訊 | 詳細內容 |
| --- | --- |
| 🧩 授權 | MIT |
| 🌐 網路需求 | 核心 OCR 流程不需網路 |
| 💻 平台 | Windows 7 x64+ / Linux x64 |
| 🛠 使用模式 | GUI、CLI、HTTP API |
| 🌍 在地化 | 以 Weblate 為基礎的社群協作 |

### 實務工作流設計

| 工作流 | 核心能力 |
| --- | --- |
| 截圖處理 | 直接從即時畫面裁切、選取並辨識文字 |
| 批次處理 | 批次處理資料夾、調整後處理，輸出結構化文字結果 |
| 文件 OCR | 掃描文件 OCR，輸出可搜尋的分層 PDF |
| QR 作業 | 同時解碼多個代碼，並產生自訂 QR / 條碼檔案 |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## 目錄

- [✨ 功能特性](#features)
- [🧱 專案結構](#project-structure)
- [🧰 前置需求](#prerequisites)
- [⚙️ 安裝](#installation)
- [⬇️ 下載發行版](#download-releases)
- [🧪 使用方式](#usage)
- [🔧 設定](#configuration)
- [🧩 範例](#examples)
- [📡 API 參考](#api-references)
- [🧠 開發備註](#development-notes)
- [🛠️ 疑難排解](#troubleshooting)
- [🌐 在地化](#localization)
- [🗺️ 發展路線](#roadmap)
- [🤝 貢獻](#contribution)
- [❤️ Support](#support)
- [📜 授權條款](#license)

<a id="features"></a>

## 功能特性

### 截圖 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- 開啟「截圖 OCR」頁籤後，使用截圖熱鍵啟動辨識。
- 左側面板可在圖片預覽中直接選取文字。
- 右側面板提供可編輯的辨識歷史與多筆複製。
- 支援從剪貼簿貼上圖片。
- 公式辨識可參考：[Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### 文字後處理（版面解析）

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

內建方案可重新排序 OCR 區塊以提升閱讀性：

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation`（適合程式碼片段）
- `No post-processing`（原始 OCR 輸出）

若所選 OCR 引擎模型支援，這些方案可同時處理橫向與縱向（由右至左）版面。

### 批次 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 輸入格式：`jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 輸出格式：`txt, jsonl, md, csv(Excel)`
- 支援沿用截圖 OCR 的文字後處理規則。
- 在 UI 工作流程中基本無任務數量上限（單次可處理上百張影像）。
- 支援任務完成後自動關機／休眠。
- 影像過大時，調整 `OCR settings -> image side limit`。

#### 忽略區域

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- 在批次 OCR 中排除固定浮水印/Logo 文字。
- 在忽略區域編輯器可用滑鼠右鍵繪製多個矩形。
- 建議將矩形繪製為略大於目標浮水印範圍以提高穩定度。
- 忽略行為採用區塊模式（落入區域的文字區塊將被忽略）。

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 文件 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 輸入格式：`pdf, xps, epub, mobi, fb2, cbz`
- 有內嵌文字時先擷取文字，否則對掃描頁面進行 OCR。
- 可匯出可搜尋的分層 PDF。
- 支援忽略區域（用於頁首/頁尾）。
- 支援任務完成後自動關機／休眠。

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

讀取模式：

- 截圖、貼上，或拖曳本機圖片進行解碼。
- 支援單張圖片中的多個代碼。
- 支援 19 種格式：

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

產生模式：

- 從文字產生 QR / 條碼圖片。
- 支援格式選擇與錯誤更正參數。

### 全域設定

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- 新增快捷鍵與啟動行為。
- 切換介面語言。
- 切換主題（淺色／深色）。
- 調整字型與 UI 縮放。
- 切換 OCR 外掛。
- 當 GPU 加速造成閃爍或畫面位移時，可切換渲染器（`Interface and Appearance -> Renderer`）。

<a id="project-structure"></a>

## 專案結構

### 倉庫關係

- [主倉庫](https://github.com/hiroi-sora/Umi-OCR)
- [外掛倉庫](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows 執行時倉庫](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 執行時倉庫](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### 執行時目錄結構（上游標準版）

`**` 表示此主倉庫包含的內容。

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

### 本倉庫快照中的原始碼樹

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

## 前置需求

### 終端使用者

| 項目 | 需求 |
| --- | --- |
| 作業系統 | Windows 7 x64+ 或 Linux x64 |
| CPU（建議） | 支援 AVX 的 x64 CPU（供 PaddleOCR 為基礎的外掛使用） |
| 執行時（建議 Windows） | Visual C++ runtime（用於相容性） |

### 開發者

- 請先閱讀並遵循平台執行時設定：
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- 本倉庫未提供可直接以 pip 安裝的獨立 `requirements.txt` 或 `pyproject.toml`。

<a id="installation"></a>

## 安裝

### 選項 A：隨身套件（建議）

1. 下載 `.7z` 或自展開 `.7z.exe` 套件。
2. 解壓縮檔案。
3. 啟動 `Umi-OCR.exe`。

### 選項 B：Scoop（Windows）

```bash
scoop bucket add extras
```

RapidOCR 版本（兼容性更佳）：

```bash
scoop install extras/umi-ocr
```

PaddleOCR 版本（稍快）：

```bash
scoop install extras/umi-ocr-paddle
```

請勿同時安裝兩個版本（可能發生快捷鍵衝突），必要時使用外掛切換。

### 選項 C：使用執行時倉庫建置／執行

依照建置／執行說明：

- [Windows 執行時安裝](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 執行時安裝](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="download-releases"></a>

## 下載發行版

| 鏡像 | 連結 | 說明 |
| --- | --- | --- |
| 藍奏雲 | [區域鏡像](https://hiroi-sora.lanzoul.com/s/umi-ocr) | 適合中國大陸區域的鏡像 |
| GitHub | [最新發行版](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | 上游主發行頁面 |
| SourceForge | [下載鏡像](https://sourceforge.net/projects/umi-ocr) | 傳統備用通道 |

<a id="usage"></a>

## 使用方式

### 快速開始

- Umi-OCR 為隨身軟體，無需安裝程式。
- 解壓後直接啟動 `Umi-OCR.exe`。
- 啟動失敗請參考[疑難排解](#troubleshooting)。

### 介面語言

首次啟動時，介面會依系統地區設定自動選擇。

手動切換：`Global Settings -> Language`。

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### 分頁與工作流程

- 只開啟你工作流需要的頁籤。
- 可從分頁列左上角切換「置頂」。
- 可從右上角鎖定分頁，防止誤關閉。

### 命令列用法

CLI 手冊：[docs/README_CLI.md](docs/README_CLI.md)

基本指令：

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

OCR 指令：

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

固定區域擷取：

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

QR 指令：

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

| 端點 | 用途 |
| --- | --- |
| `/api/ocr/get_options` | OCR 選項 |
| `/api/ocr` | 執行 OCR |
| `/api/doc/*` | 文件選項/上傳/結果/下載 |
| `/api/qrcode` | QR 解碼 |
| `/argv` | 透過 HTTP 將 CLI 作為橋接 |

注意：在 `Global Settings` 中，HTTP 服務必須保持啟用（預設值）。除非需要 LAN 存取，否則請使用僅本機位址。

<a id="configuration"></a>

## 設定

- 執行時設定儲存於 `UmiOCR-data/.settings`（INI 格式）。
- 手動修改設定後，請以以下方式套用：

```bash
umi-ocr --reload
```

- 某些啟動／執行時相容性狀態也可能涉及：
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/`（適用於有執行時日誌的版本）

<a id="examples"></a>

## 範例

### 範例 1：依路徑批次 OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 範例 2：從多個路徑讀取 QR

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 範例 3：指定尺寸產生 QR

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### 範例 4：高階模組調用

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

<a id="api-references"></a>

## API 參考

- 命令列手冊：[docs/README_CLI.md](docs/README_CLI.md)
- HTTP API 手冊：[docs/http/README.md](docs/http/README.md)
- OCR API：[docs/http/api_ocr.md](docs/http/api_ocr.md)
- 文件 API：[docs/http/api_doc.md](docs/http/api_doc.md)
- QR API：[docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv 橋接：[docs/http/argv.md](docs/http/argv.md)

<a id="development-notes"></a>

## 開發備註

- 進入點：
  - `UmiOCR-data/main.py`（執行時初始化）
  - `UmiOCR-data/py_src/run.py`（應用程式啟動）
- UI 技術棧：PySide2 + QML（`UmiOCR-data/qt_res/qml`）。
- 核心服務：
  - `py_src/server/*`（HTTP + 指令傳輸）
  - `py_src/mission/*`（OCR/文件/QR 佇列任務）
  - `py_src/ocr/*`（OCR 後處理與輸出）
- 生態系支援的 OCR 引擎：
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- 執行時框架：[PyStand（已客製化）](https://github.com/skywind3000/PyStand)

<a id="troubleshooting"></a>

## 疑難排解

完整排錯細節請參考： [https://github.com/hiroi-sora/Umi-OCR/issues/447](https://github.com/hiroi-sora/Umi-OCR/issues/447)

快速索引：

| 現象 | 導向 |
| --- | --- |
| 找不到 `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| 建立 OpenGL context 失敗 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 應用程式啟動時當機 | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 初始化失敗（MKLDNN/AVX 提示） | [`0xc0000142` 或 OCR 初始化失敗（MKLDNN/AVX 提示）](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| 缺少 `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- 安裝 VC runtime： https://aka.ms/vs/17/release/vc_redist.x64.exe
- 或使用備援啟動方式 `UmiOCR-data/RUN_GUI.bat`。
- 注意：`.bat` 啟動方式有限制（無 CLI 控制、快捷鍵自動化功能有限）。

### `Failed to create OpenGL context`

- 下載執行時修補： https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 將解壓後的 DLL 放入 `UmiOCR-data/site-packages/PySide2/`。

### `Umi-OCR.exe has stopped working`

- 常見於不同 Windows 版本間共用設定。
- 刪除 `UmiOCR-data/.pre_settings` 後重試。

### `0xc0000142` 或 OCR 初始化失敗（MKLDNN/AVX 提示）

- 可能是 CPU 不支援 AVX。
- 改用 RapidOCR 變體，或切換到非 PaddleOCR 外掛：
  - [Umi-OCR_Rapid 發行版](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### `黑色主控台與 OSError（程式未找到）`

- 常見於未套用修補的早期 Windows 7（尤其缺少 `KB2533623`）。
- 建議修復：完成 Windows Update 後重新開機。

### 匯出可搜尋 PDF 時當機

- 常見原因是缺少 Windows 7 更新（尤其是 `KB4534310` 及相依元件）。
- 建議修復：透過 Windows Update 安裝所有缺失更新。

### 缺少 `api-ms-win-crt-runtime-l1-1-0.dll`

- 安裝 VC runtime： https://aka.ms/vs/17/release/vc_redist.x64.exe

### 手動放置捷徑

若自動建立捷徑失敗，請手動放置：

- 開始功能表：`C:\ProgramData\Microsoft\Windows\Start Menu`
- 開機啟動：`C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

<a id="localization"></a>

## 在地化

本專案採用 Weblate 進行協作式在地化：

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

本倉庫中的 README 語言檔：

| 語言 | 檔案 |
| --- | --- |

感謝所有翻譯者：

| 翻譯者 | 貢獻語言 |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

若有錯誤或遺漏，請前往[討論區回報](https://github.com/hiroi-sora/Umi-OCR/discussions/449)。

<a id="roadmap"></a>

## 路線圖

### 已完成

- 標籤頁架構。
- OCR API 控制器。
- OCR 任務控制器。
- 淺色／深色主題管理器。
- 批次 OCR。
- 截圖 OCR。
- 熱鍵機制。
- 系統匣選單。
- 文字區塊後處理（版面最佳化）。
- 引擎記憶體清理。
- 多語系 UI。
- 命令列模式。
- Windows 7 相容性。
- Excel（CSV）輸出格式。
- `Esc` 截圖中斷。
- 外部主題檔。
- 字型切換。
- 載入動畫。
- 忽略區域。
- QR 碼識別。
- 批次辨識中的影像預覽。
- PDF 辨識。
- 用本機影像檢視器開啟影像。[#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- 重複上次截圖區域。[#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- 修正 Windows 7 文件辨識相容性問題。
- 在 HTTP 與 CLI 介面加入 QR 讀取/產生支援。（#423）
- QR 介面文件。
- Linux 平台移轉。
- HTTP 文件辨識 API。

### 長期規劃

以下項目為規劃中的構想，可能隨開發調整：

- [ ] 重構底層外掛機制。
- [ ] 線上 OCR API 外掛。
- [ ] 獨立公式辨識外掛。
- [ ] 專用公式頁籤與 LaTeX 呈現。
- [ ] 更新檢查機制。
- [ ] 除版面解析以外的其他後處理模組。
- [ ] 介面主要功能的事件觸發。
- [ ] 基於 GPU 的離線 OCR。
- [ ] 圖片翻譯。
- [ ] 離線翻譯。
- [ ] 固定區域 OCR。
- [ ] 表格辨識並輸出至 Excel。
- [ ] 歷史紀錄系統。
- [ ] 擴充 macOS/Ubuntu 等平台相容性。

<a id="contribution"></a>

## 貢獻

歡迎任何形式的貢獻。

- 透過 [Issues](https://github.com/hiroi-sora/Umi-OCR/issues) 回報錯誤或提報需求。
- 在 [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) 討論想法。
- 透過 [Weblate](https://hosted.weblate.org/engage/umi-ocr/) 參與翻譯。
- 若要參與引擎或外掛開發，另請參考 [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)。

開發環境請依各平台執行時倉庫文件：

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="support"></a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

<a id="license"></a>

## 授權條款

本專案採用 MIT 授權條款。

- [LICENSE](LICENSE)


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
