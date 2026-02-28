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
    <a href="#table-of-contents">使用说明</a>
    <span> • </span>
    <a href="#download-releases">下载发行版</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">更新日志</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">问题反馈</a>
  </h3>
</div>

<div align="center">
  <strong>免费、开源、支持批处理的离线 OCR 软件</strong><br>
  <sub>兼容 Windows 7 x64 与 Linux x64</sub>
</div>

## 🚀 一览

| 关注点 | 详情 |
| --- | --- |
| 📦 发行 | 便携式桌面应用（`.7z` 与 `.7z.exe`） |
| 🧠 核心模式 | 支持截图、文档与二维码的离线批量 OCR 工作流 |
| 🧩 接口 | GUI、CLI 与 HTTP API |
| 🌐 本地化 | 通过 Weblate 由社区协作翻译 |

---

<a id="overview"></a>

## 概览

Umi-OCR 是一款桌面优先的 OCR 工具，专注于离线处理、高吞吐批量工作流和可落地的集成能力。

- **免费**：全部代码开源，永久免费使用。
- **便捷**：本地提取和运行，无需核心 OCR 网络依赖。
- **高效**：内置离线 OCR 引擎并支持多语言。
- **灵活**：支持 GUI 工作流、命令行控制和 HTTP API。
- **功能丰富**：支持截图 OCR、批量 OCR、文档 OCR、二维码识读与生成、公式识别入口。

| ✅ 快速信息 | 详情 |
| --- | --- |
| 🧩 许可证 | MIT |
| 🌐 网络要求 | 核心 OCR 工作流无需联网 |
| 💻 平台 | Windows 7 x64+ / Linux x64 |
| 🛠 使用模式 | GUI、CLI、HTTP API |
| 🌍 翻译 | 基于 Weblate 的社区本地化 |

### 面向实际工作流设计

| 工作流 | 核心能力 |
| --- | --- |
| 截图处理 | 从实时截图中直接裁切、选区并转写文字 |
| 批量处理 | 处理文件夹、调整后处理并导出结构化文本结果 |
| 文档 OCR | 识别扫描文档并生成可搜索的分层 PDF |
| 二维码操作 | 解码多个二维码并生成自定义二维码/条码资源 |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

<a id="table-of-contents"></a>

## 目录

- [✨ 特性](#features)
- [🧱 项目结构](#project-structure)
- [🧰 前置条件](#prerequisites)
- [⚙️ 安装](#installation)
- [⬇️ 下载发行版](#download-releases)
- [🧪 使用](#usage)
- [🔧 配置](#configuration)
- [🧩 示例](#examples)
- [📡 API 参考](#api-references)
- [🧠 开发说明](#development-notes)
- [🛠️ 故障排查](#troubleshooting)
- [🌐 本地化](#localization)
- [🗺️ 路线图](#roadmap)
- [🤝 贡献](#contribution)
- [❤️ Support](#support)
- [📜 许可证](#license)

## 功能特性

<a id="features"></a>

### 截图 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- 打开截图 OCR 页签后，可通过截图快捷键触发 OCR。
- 左侧面板支持在图片预览中直接选取文本。
- 右侧面板支持可编辑的识别历史，并可多条记录复制。
- 支持粘贴来自剪贴板的图片。
- 公式识别参考：[Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### 文本后处理（版面解析）

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

内置方案用于重排 OCR 文本块并提升可读性：

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation`（适合代码片段）
- `No post-processing`（原始 OCR 输出）

这些方案可处理横排与竖排（从右到左）版式（前提是所选 OCR 引擎模型支持该方向）。

### 批量 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 输入格式：`jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 输出格式：`txt, jsonl, md, csv(Excel)`
- 支持截图 OCR 的文本后处理规则。
- 在界面工作流中几乎没有实际任务数量上限（单次支持数百张图片）。
- 支持任务完成后自动关机/休眠。
- 对超大图片，可调整 `OCR settings -> image side limit`。

#### 忽略区域

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- 在批量 OCR 时可排除固定水印或 logo 文本。
- 在忽略区域编辑器中可用鼠标右键绘制多个矩形。
- 建议绘制略大于目标水印区域的矩形以提高鲁棒性。
- 忽略行为以文本块为单位（区域内文本块将被忽略）。

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 文档 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 输入格式：`pdf, xps, epub, mobi, fb2, cbz`
- 优先提取内嵌文本；无文本时执行扫描页 OCR。
- 导出可搜索分层 PDF。
- 支持忽略区域（用于页眉/页脚）。
- 支持任务完成后自动关机/休眠。

### 二维码

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

读取模式：

- 支持截图、粘贴或拖拽本地图片解码。
- 支持单张图片识别多个码。
- 支持 19 种格式：

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

生成模式：

- 根据文本生成二维码或条码图像。
- 支持格式选择与纠错设置。

### 全局设置

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- 添加快捷键并配置启动行为。
- 切换界面语言。
- 切换主题（明暗色变体）。
- 配置字体与界面缩放。
- 切换 OCR 插件。
- 当 GPU 加速导致闪烁或界面错位时，可切换渲染器（`Interface and Appearance -> Renderer`）。

<a id="project-structure"></a>

## 项目结构

### 仓库关系

- [主仓库](https://github.com/hiroi-sora/Umi-OCR)
- [插件仓库](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows 运行时仓库](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 运行时仓库](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### 运行时目录结构（上游标准布局）

`**` 表示本仓库内包含的内容。

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

### 当前仓库快照中的源码树

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

## 前置条件

### 终端用户

| 条目 | 要求 |
| --- | --- |
| 操作系统 | Windows 7 x64+ 或 Linux x64 |
| CPU（推荐） | 支持 AVX 的 x64 CPU（用于基于 PaddleOCR 的插件） |
| 运行时（Windows 推荐） | 为兼容性提供 Visual C++ 运行库 |

### 开发者

- 请先阅读并遵循以下平台运行时配置：
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- 本仓库不提供用于直接 `pip` 安装的独立 `requirements.txt` 或 `pyproject.toml`。

<a id="installation"></a>

## 安装

### 方案 A：便携发行包（推荐）

1. 下载 `.7z` 或自解压 `.7z.exe` 包。
2. 解压文件。
3. 启动 `Umi-OCR.exe`。

### 方案 B：Scoop（Windows）

```bash
scoop bucket add extras
```

RapidOCR 变体（兼容性更好）：

```bash
scoop install extras/umi-ocr
```

PaddleOCR 变体（速度略快）：

```bash
scoop install extras/umi-ocr-paddle
```

请勿同时安装两个变体（可能发生快捷方式冲突）。如有需要，可通过插件切换。

### 方案 C：通过运行时仓库构建/运行

按下列仓库中的构建/运行时初始化说明操作：

- [Windows 运行时设置](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 运行时设置](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="download-releases"></a>

## 下载发行版

| 镜像站 | 链接 | 说明 |
| --- | --- | --- |
| 蓝奏云 | [Regional mirror](https://hiroi-sora.lanzoul.com/s/umi-ocr) | 友好的区域镜像 |
| GitHub | [Latest releases](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | 上游主发布页 |
| SourceForge | [Download mirror](https://sourceforge.net/projects/umi-ocr) | 传统备用渠道 |

<a id="usage"></a>

## 使用

### 入门

- Umi-OCR 为便携应用，无需安装器。
- 解压后启动 `Umi-OCR.exe`。
- 若启动失败，请查看[故障排查](#troubleshooting)。

### 界面语言

首次启动时，界面语言将按系统区域自动选择。

手动切换：`Global Settings -> Language`。

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### 标签页与工作流

- 仅打开工作流所需的标签页。
- 在标签栏左上角切换窗口置顶。
- 从右上角锁定标签页，防止误关闭。

### 命令行用法

CLI 手册：[docs/README_CLI.md](docs/README_CLI.md)

基础控制：

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

固定区域截图：

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

二维码命令：

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

输出选项：

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr "-->>" result.txt
```

### HTTP API 用法

HTTP 文档：[docs/http/README.md](docs/http/README.md)

核心端点：

| 端点 | 用途 |
| --- | --- |
| `/api/ocr/get_options` | OCR 选项 |
| `/api/ocr` | 执行 OCR |
| `/api/doc/*` | 文档选项/上传/结果/下载 |
| `/api/qrcode` | 二维码解码 |
| `/argv` | HTTP 上的 CLI 桥接 |

说明：在`Global Settings` 中，HTTP 服务必须保持开启（默认开启）。仅在需要局域网访问时启用非本地监听。

<a id="configuration"></a>

## 配置

- 运行时配置保存在 `UmiOCR-data/.settings`（INI 格式）。
- 手动编辑配置后，可通过以下命令应用变更：

```bash
umi-ocr --reload
```

- 一些启动/运行时兼容状态也可能涉及：
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/`（针对带运行时日志的版本）

<a id="examples"></a>

## 示例

### 示例 1：按路径执行批量 OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 示例 2：读取多个路径中的二维码

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 示例 3：按指定尺寸生成二维码

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### 示例 4：高级模块调用

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

<a id="api-references"></a>

## API 参考

- 命令行手册：[docs/README_CLI.md](docs/README_CLI.md)
- HTTP API 手册：[docs/http/README.md](docs/http/README.md)
- OCR API：[docs/http/api_ocr.md](docs/http/api_ocr.md)
- 文档 API：[docs/http/api_doc.md](docs/http/api_doc.md)
- 二维码 API：[docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv 桥接：[docs/http/argv.md](docs/http/argv.md)

<a id="development-notes"></a>

## 开发说明

- 入口点：
  - `UmiOCR-data/main.py`（运行时启动）
  - `UmiOCR-data/py_src/run.py`（应用启动）
- UI 技术栈：PySide2 + QML（`UmiOCR-data/qt_res/qml`）。
- 核心服务：
  - `py_src/server/*` 用于 HTTP 与命令传输
  - `py_src/mission/*` 用于 OCR/文档/二维码队列任务
  - `py_src/ocr/*` 用于 OCR 后处理与输出
- 生态支持的 OCR 引擎：
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- 运行时框架：[PyStand（定制版）](https://github.com/skywind3000/PyStand)

<a id="troubleshooting"></a>

## 故障排查

完整排障细节见： https://github.com/hiroi-sora/Umi-OCR/issues/447

快速索引：

| 症状 | 跳转 |
| --- | --- |
| 找不到 `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL 上下文创建失败 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 程序启动崩溃 | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 初始化失败 | [`0xc0000142` 或 `MKLDNN/AVX` 提示导致的初始化失败](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| 缺少 `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- 安装 VC 运行库： https://aka.ms/vs/17/release/vc_redist.x64.exe
- 或通过备用方式启动 `UmiOCR-data/RUN_GUI.bat`。
- 注意：`.bat` 启动方式有局限（无法进行 CLI 控制，快捷键自动化能力有限）。

### `Failed to create OpenGL context`

- 下载运行时补丁： https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 将解压的 DLL 放入 `UmiOCR-data/site-packages/PySide2/`。

### `Umi-OCR.exe has stopped working`

- 常见于跨不同 Windows 版本复用配置后。
- 删除 `UmiOCR-data/.pre_settings` 后重试。

### `0xc0000142` 或 `MKLDNN/AVX` 提示导致 OCR 初始化失败

- 可能是 CPU 不支持 AVX。
- 请使用 RapidOCR 变体或切换为非 PaddleOCR 插件：
  - [Umi-OCR_Rapid 发行版](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR 插件](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- 常见于未打补丁的早期 Windows 7（特别是缺少 `KB2533623`）。
- 建议修复：运行完整 Windows 更新并重启。

### Crash while exporting searchable PDF

- 常见原因是缺少 Windows 7 更新（尤其是 `KB4534310` 及其依赖）。
- 建议修复：通过 Windows Update 安装所有缺失的系统更新。

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- 安装 VC 运行库： https://aka.ms/vs/17/release/vc_redist.x64.exe

### 手动放置快捷方式

如果自动创建快捷方式失败，请手动放置：

- 开始菜单：`C:\ProgramData\Microsoft\Windows\Start Menu`
- 启动项：`C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

<a id="localization"></a>

## 本地化

本项目使用 Weblate 进行协作本地化：

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

本仓库中的 README 多语言文件：

| 语言 | 文件 |
| --- | --- |

感谢所有翻译者：

| 翻译者 | 贡献语言 |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

如果有错误或遗漏，请在[该讨论区](https://github.com/hiroi-sora/Umi-OCR/discussions/449)回复。

<a id="roadmap"></a>

## 路线图

### 已完成

- 标签页架构。
- OCR API 控制器。
- OCR 任务/mission 控制器。
- 支持明暗色的主题管理器。
- 批量 OCR。
- 截图 OCR。
- 热键机制。
- 系统托盘菜单。
- 文本块后处理（布局优化）。
- 引擎内存清理。
- 多语言界面。
- 命令行模式。
- Windows 7 兼容性。
- Excel（CSV）输出格式。
- `Esc` 截图中断。
- 外部主题文件。
- 字体切换。
- 加载动画。
- 忽略区域。
- 二维码识别。
- 批量识别中的图片预览。
- PDF 识别。
- 使用本地图片查看器打开图像。[#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- 重复上一次截图区域。[#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- 修复文档识别在 Windows 7 下的兼容性问题。
- HTTP 与 CLI 接口二维码读取/生成支持。（#423）
- 二维码接口文档。
- Linux 平台迁移。
- HTTP 文档识别 API。

### 长期计划

以下条目为计划中的想法，可能在开发过程中调整：

- [ ] 重构底层插件机制。
- [ ] 在线 OCR API 插件。
- [ ] 独立公式识别插件。
- [ ] 专用公式标签页和 LaTeX 渲染。
- [ ] 更新检测机制。
- [ ] 在版式解析之外增加更多后处理模块。
- [ ] 关键界面功能的事件触发器。
- [ ] 基于 GPU 的离线 OCR。
- [ ] 图片翻译。
- [ ] 离线翻译。
- [ ] 固定区域 OCR。
- [ ] 表格识别并导出 Excel。
- [ ] 历史记录系统。
- [ ] 扩展到 macOS/Ubuntu 等平台的兼容性。

<a id="contribution"></a>

## 贡献

欢迎贡献。

- 通过 [Issues](https://github.com/hiroi-sora/Umi-OCR/issues) 报告缺陷或提出功能请求。
- 在 [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) 中讨论想法。
- 通过 [Weblate](https://hosted.weblate.org/engage/umi-ocr/) 贡献翻译。
- 进行引擎/插件工作请参考 [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)。

开发环境搭建请参考平台运行时仓库：

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

<a id="change-log"></a>

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

<a id="license"></a>

## 许可证

本项目采用 MIT 许可证。

- [LICENSE](LICENSE)


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
