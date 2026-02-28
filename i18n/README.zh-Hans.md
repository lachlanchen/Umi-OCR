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

## 概览

Umi-OCR 是一款以桌面端为核心的 OCR 工具，重点面向离线处理、高吞吐批量工作流，以及实用的集成能力。

- **免费**：全部代码开源，永久免费使用。
- **便捷**：解压即用，核心 OCR 不依赖网络。
- **高效**：内置离线 OCR 引擎，支持多语言识别。
- **灵活**：支持 GUI 工作流、命令行控制与 HTTP API。
- **功能丰富**：支持截图 OCR、批量 OCR、文档 OCR、二维码识别/生成、公式识别入口。

| ✅ 快速信息 | 详情 |
| --- | --- |
| 🧩 许可证 | MIT |
| 🌐 网络要求 | 核心 OCR 工作流无需联网 |
| 💻 平台 | Windows 7 x64+ / Linux x64 |
| 🛠 使用模式 | GUI、CLI、HTTP API |
| 🌍 翻译 | 基于 Weblate 的社区本地化 |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

<a id="table-of-contents"></a>

## 目录

- [功能特性](#features)
- [项目结构](#project-structure)
- [前置条件](#prerequisites)
- [安装](#installation)
- [下载发行版](#download-releases)
- [使用](#usage)
- [配置](#configuration)
- [示例](#examples)
- [API 参考](#api-references)
- [开发说明](#development-notes)
- [故障排查](#troubleshooting)
- [本地化](#localization)
- [路线图](#roadmap)
- [贡献](#contribution)
- [支持](#support)
- [许可证](#license)

<a id="features"></a>

## 功能特性

### 截图 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- 打开截图 OCR 标签页后，可通过截图快捷键触发 OCR。
- 左侧面板支持在图片预览中直接选取文本。
- 右侧面板支持可编辑识别历史及多条记录复制。
- 支持粘贴来自剪贴板的图片。
- 公式识别参考：[Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### 文本后处理（版面解析）

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

内置方案可对 OCR 文本块重排，提升可读性：

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation`（适合代码片段）
- `No post-processing`（原始 OCR 输出）

若所选 OCR 引擎模型支持，这些方案可处理横排与竖排（从右到左）版式。

### 批量 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 输入格式：`jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 输出格式：`txt, jsonl, md, csv(Excel)`
- 支持截图 OCR 的文本后处理规则。
- 在 UI 工作流中基本没有实际任务数量上限（单次支持数百张图片）。
- 支持任务完成后自动关机/睡眠。
- 对超大图片，请调整 `OCR settings -> image side limit`。

#### 忽略区域

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- 在批量 OCR 时排除固定水印/Logo 文本。
- 在忽略区域编辑器中，可用鼠标右键绘制多个矩形。
- 建议绘制略大于目标水印区域的矩形，以提高鲁棒性。
- 忽略逻辑以文本块为单位（区域内文本块会被忽略）。

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 文档 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 输入格式：`pdf, xps, epub, mobi, fb2, cbz`
- 有内嵌文本时优先提取，否则对扫描页执行 OCR。
- 可导出可搜索的分层 PDF。
- 支持忽略区域（适用于页眉/页脚）。
- 支持任务完成后自动关机/睡眠。

### 二维码

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

读取模式：

- 支持截图、粘贴或拖拽本地图片进行解码。
- 支持单图多码识别。
- 支持 19 种格式：

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

生成模式：

- 可将文本生成二维码/条形码图片。
- 支持格式选择与纠错等级设置。

### 全局设置

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- 添加快捷键并配置启动行为。
- 切换界面语言。
- 切换主题（浅色/深色变体）。
- 配置字体与 UI 缩放。
- 切换 OCR 插件。
- 当 GPU 加速导致闪烁或界面错位时，可切换渲染器（`Interface and Appearance -> Renderer`）。

<a id="project-structure"></a>

## 项目结构

### 仓库关系

- [主仓库](https://github.com/hiroi-sora/Umi-OCR)
- [插件仓库](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows 运行时仓库](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 运行时仓库](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### 运行时目录结构（上游规范布局）

`**` 表示内容包含在当前主仓库中。

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

### 当前仓库快照的源码树

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

| 项目 | 要求 |
| --- | --- |
| 操作系统 | Windows 7 x64+ 或 Linux x64 |
| CPU（推荐） | 支持 AVX 的 x64 CPU（用于基于 PaddleOCR 的插件） |
| 运行时（Windows 推荐） | 用于兼容性的 Visual C++ 运行库 |

### 开发者

- 请先阅读并遵循以下平台运行时环境配置：
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- 本仓库不提供可直接用于 pip 安装的独立 `requirements.txt` 或 `pyproject.toml`。

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

请勿同时安装两个变体（可能发生快捷方式冲突）。如有需要，请通过插件切换。

### 方案 C：通过运行时仓库构建/运行

请按照以下仓库的构建/运行时引导说明操作：

- [Windows 运行时配置](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 运行时配置](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="download-releases"></a>

## 下载发行版

| 镜像 | 链接 | 说明 |
| --- | --- | --- |
| 蓝奏云 | https://hiroi-sora.lanzoul.com/s/umi-ocr | 区域镜像 |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | 上游主发行页面 |
| SourceForge | https://sourceforge.net/projects/umi-ocr | 备用下载镜像 |

<a id="usage"></a>

## 使用

### 快速开始

- Umi-OCR 为便携版，无需安装程序。
- 解压后启动 `Umi-OCR.exe`。
- 若启动失败，请查看[故障排查](#troubleshooting)。

### 界面语言

首次启动时，界面语言会根据系统区域自动选择。

手动切换路径：`Global Settings -> Language`。

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### 标签页与工作流

- 仅打开当前工作流所需的标签页。
- 可在标签栏左上角切换窗口置顶。
- 可在右上角锁定标签页，防止误关闭。

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
umi-ocr --screenshot "-->>" result.txt
```

### HTTP API 用法

HTTP 文档：[docs/http/README.md](docs/http/README.md)

关键端点：

| Endpoint | 用途 |
| --- | --- |
| `/api/ocr/get_options` | OCR 选项 |
| `/api/ocr` | 执行 OCR |
| `/api/doc/*` | 文档选项/上传/结果/下载 |
| `/api/qrcode` | 二维码解码 |
| `/argv` | 通过 HTTP 调用 CLI 桥接 |

注意：在 `Global Settings` 中需保持 HTTP 服务开启（默认开启）。除非需要局域网访问，否则建议仅使用本地监听地址。

<a id="configuration"></a>

## 配置

- 运行时设置保存在 `UmiOCR-data/.settings`（INI 格式）。
- 手动编辑配置后，可通过以下命令应用变更：

```bash
umi-ocr --reload
```

- 某些启动/运行时兼容状态也可能涉及：
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/`（含运行时日志的版本）

<a id="examples"></a>

## 示例

### 示例 1：按路径批量 OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 示例 2：从多个路径读取二维码

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 示例 3：指定尺寸生成二维码

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
  - `UmiOCR-data/main.py`（运行时引导）
  - `UmiOCR-data/py_src/run.py`（应用启动）
- UI 技术栈：PySide2 + QML（`UmiOCR-data/qt_res/qml`）。
- 核心服务：
  - `py_src/server/*` 用于 HTTP 与命令传输
  - `py_src/mission/*` 用于队列化 OCR/文档/二维码任务
  - `py_src/ocr/*` 用于 OCR 后处理与输出
- 生态支持的 OCR 引擎：
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- 运行时框架：[PyStand（定制版）](https://github.com/skywind3000/PyStand)

<a id="troubleshooting"></a>

## 故障排查

完整排障说明： https://github.com/hiroi-sora/Umi-OCR/issues/447

快速索引：

| 症状 | 跳转 |
| --- | --- |
| 找不到 `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL 上下文创建失败 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 程序启动即崩溃 | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 初始化失败 | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| 缺少 `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- 安装 VC 运行库：https://aka.ms/vs/17/release/vc_redist.x64.exe
- 或使用备用启动方式 `UmiOCR-data/RUN_GUI.bat`。
- 注意：`.bat` 启动方式有局限（不支持 CLI 控制、快捷键自动化能力有限）。

### `Failed to create OpenGL context`

- 下载运行时补丁：https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 将解压后的 DLL 放到 `UmiOCR-data/site-packages/PySide2/`。

### `Umi-OCR.exe has stopped working`

- 常见于在不同 Windows 版本间复用配置后。
- 删除 `UmiOCR-data/.pre_settings` 后重试。

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- 通常是 CPU 不支持 AVX。
- 请使用 RapidOCR 变体，或切换为非 PaddleOCR 插件：
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- 常见于未打补丁的早期 Windows 7（尤其缺少 `KB2533623`）。
- 建议修复：运行完整 Windows Update 并重启。

### Crash while exporting searchable PDF

- 常由 Windows 7 缺少更新导致（尤其 `KB4534310` 及其依赖）。
- 建议修复：通过 Windows Update 安装所有缺失的系统更新。

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- 安装 VC 运行库：https://aka.ms/vs/17/release/vc_redist.x64.exe

### 手动放置快捷方式

若自动创建快捷方式失败，可手动放置：

- 开始菜单：`C:\ProgramData\Microsoft\Windows\Start Menu`
- 启动项：`C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

<a id="localization"></a>

## 本地化

本项目使用 Weblate 进行协作翻译：

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

本仓库中的 README 多语言文件：

| 语言 | 文件 |
| --- | --- |

感谢所有翻译贡献者：

| 翻译者 | 贡献语言 |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

如果有错误或遗漏，欢迎在[此讨论](https://github.com/hiroi-sora/Umi-OCR/discussions/449)回复。

<a id="roadmap"></a>

## 路线图

### 已完成

- 标签页架构。
- OCR API 控制器。
- OCR mission/task 控制器。
- 支持浅色/深色的主题管理器。
- 批量 OCR。
- 截图 OCR。
- 热键机制。
- 系统托盘菜单。
- 文本块后处理（布局优化）。
- 引擎内存清理。
- 多语言界面。
- 命令行模式。
- Windows 7 兼容。
- Excel（CSV）输出格式。
- 截图时支持 `Esc` 中断。
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
- HTTP 与 CLI 接口支持二维码读取/生成。（#423）
- 二维码接口文档。
- Linux 平台迁移。
- HTTP 文档识别 API。

### 长期计划

以下条目为规划中的想法，可能在开发过程中调整：

- [ ] 重构底层插件机制。
- [ ] 在线 OCR API 插件。
- [ ] 独立的公式识别插件。
- [ ] 专用公式标签页与 LaTeX 渲染。
- [ ] 更新检测机制。
- [ ] 除版面解析外的更多后处理模块。
- [ ] 关键界面功能的事件触发器。
- [ ] 基于 GPU 的离线 OCR。
- [ ] 图片翻译。
- [ ] 离线翻译。
- [ ] 固定区域 OCR。
- [ ] 表格识别并导出为 Excel。
- [ ] 历史记录系统。
- [ ] 扩展到 macOS/Ubuntu 等平台的兼容性。

<a id="contribution"></a>

## 贡献

欢迎贡献。

- 通过 [Issues](https://github.com/hiroi-sora/Umi-OCR/issues) 提交缺陷或功能请求。
- 在 [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) 参与方案讨论。
- 通过 [Weblate](https://hosted.weblate.org/engage/umi-ocr/) 贡献翻译。
- 涉及引擎/插件开发，也请参考 [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)。

开发环境搭建请遵循以下平台运行时仓库：

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="support"></a>

## 支持

Umi-OCR 主要由 [hiroi-sora](https://github.com/hiroi-sora) 在业余时间维护与开发。

如果这个项目对你有帮助，欢迎赞助支持：

- 爱发电（中国）：https://afdian.com/a/hiroi-sora

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

<a id="license"></a>

## 许可证

本项目采用 MIT 许可证。

- [LICENSE](LICENSE)
