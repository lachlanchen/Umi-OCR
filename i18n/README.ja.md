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
  <a href="#リリースのダウンロード">
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
    <a href="#目次">使い方</a>
    <span> • </span>
    <a href="#download-releases">リリースのダウンロード</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">変更履歴</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">問題を報告</a>
  </h3>
</div>

<div align="center">
  <strong>無料・オープンソースのバッチ対応オフライン OCR ソフトウェア</strong><br>
  <sub>Windows 7 x64 および Linux x64 に対応</sub>
</div>

## 🚀 一目でわかる

| フォーカス | 詳細 |
| --- | --- |
| 📦 配布形態 | ポータブルのデスクトップアプリ (`.7z` および `.7z.exe`) |
| 🧠 コアモード | スクリーンショット・文書・QR を含むオフライン一括 OCR |
| 🧩 インターフェース | GUI、CLI、HTTP API |
| 🌐 ローカリゼーション | Weblate を通じたコミュニティ翻訳 |

---

## 概要

Umi-OCR はデスクトップ中心の OCR ツールで、オフライン処理、高スループットの一括ワークフロー、実務で使いやすい統合を重視して設計されています。

- **無料**: 全てのコードはオープンソースで、自由に利用できます。
- **使いやすい**: ローカルで抽出・実行し、コア OCR にネットワーク依存はありません。
- **効率的**: マルチ言語対応のオフライン OCR エンジンを同梱。
- **柔軟**: GUI ワークフロー、コマンドライン制御、HTTP API をサポート。
- **機能豊富**: スクリーンショット OCR、バッチ OCR、文書 OCR、QR 読み取り・作成、数式認識のエントリーポイント。

| ✅ クイック情報 | 詳細 |
| --- | --- |
| 🧩 ライセンス | MIT |
| 🌐 ネットワーク要件 | コア OCR ワークフローはネットワーク不要 |
| 💻 対応プラットフォーム | Windows 7 x64+ / Linux x64 |
| 🛠 利用モード | GUI、CLI、HTTP API |
| 🌍 翻訳 | Weblate ベースのコミュニティローカライズ |

### 実運用向けに設計

| ワークフロー | 主な機能 |
| --- | --- |
| スクリーンショット処理 | 画面キャプチャから直接トリミングして文字起こし |
| バッチ処理 | フォルダ一括処理、後処理調整、構造化テキストのエクスポート |
| 文書 OCR | スキャン済み文書を OCR し、検索可能なレイヤード PDF を作成 |
| QR 操作 | 複数コードのデコード、カスタム QR/バーコード生成 |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## 目次

- [✨ 機能](#機能)
- [🧱 プロジェクト構成](#プロジェクト構成)
- [🧰 前提条件](#前提条件)
- [⚙️ インストール](#インストール)
- [⬇️ リリースのダウンロード](#リリースのダウンロード)
- [🧪 使い方](#使い方)
- [🔧 設定](#設定)
- [🧩 サンプル](#サンプル)
- [📡 API リファレンス](#api-リファレンス)
- [🧠 開発メモ](#開発メモ)
- [🛠️ トラブルシューティング](#トラブルシューティング)
- [🌐 ローカリゼーション](#ローカリゼーション)
- [🗺️ ロードマップ](#ロードマップ)
- [🤝 貢献](#貢献)
- [❤️ Support](#support)
- [📜 ライセンス](#ライセンス)

## 機能

### スクリーンショット OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- スクリーンショット OCR タブを開いた後、ショートカットで OCR を開始。
- 左側パネルで画像プレビュー内を直接テキスト選択。
- 右側パネルで認識履歴を編集でき、複数レコードをまとめてコピー可能。
- クリップボード貼り付け画像に対応。
- 数式認識の参考: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### テキスト後処理（レイアウト解析）

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

OCR ブロックを再配置して可読性を向上させる組み込みスキーム:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation`（コードスニペットで有効）
- `No post-processing`（生 OCR 出力）

選択した OCR エンジンが対応していれば、横組み・縦組み（右から左）レイアウトの処理にも対応します。

### バッチ OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 入力形式: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 出力形式: `txt, jsonl, md, csv(Excel)`
- スクリーンショット OCR のテキスト後処理ルールを再利用可能。
- UI ワークフロー上に実質的な件数上限はなく、1 回あたり数百枚規模を想定。
- タスク完了後に自動シャットダウン/スリープへ対応。
- 超大きな画像は `OCR settings -> image side limit` を調整。

#### 除外領域

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- バッチ OCR 時に、安定した透かし・ロゴ文字を除外。
- 除外領域エディターで右クリックし、複数の矩形を描画。
- 対象透かし領域より少し大きめに矩形を描くと安定します。
- 除外はブロック単位（領域内のテキストブロックを無視）で行われます。

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 文書 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 入力形式: `pdf, xps, epub, mobi, fb2, cbz`
- テキストが埋め込まれていれば抽出し、なければスキャンページを OCR。
- 検索可能なレイヤード PDF をエクスポート。
- ヘッダー/フッター用に除外領域をサポート。
- タスク完了後に自動シャットダウン/スリープへ対応。

### QR コード

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

読み取りモード:

- スクリーンショット、貼り付け、ローカル画像のドラッグでデコード。
- 1 画像内の複数コードをサポート。
- 19 種類の形式に対応:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

生成モード:

- テキストから QR/バーコード画像を生成。
- 形式選択や誤り訂正レベルの設定に対応。

### 全体設定

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- ショートカットの追加と起動時の挙動を設定。
- UI 言語を切り替え。
- テーマ切り替え（ライト / ダーク系）。
- フォントや UI スケーリングを設定。
- OCR プラグインを切り替え。
- GPU アクセラレーションでチラつきや UI のずれが起きる場合、`Interface and Appearance -> Renderer` でレンダラーを切り替え。

## プロジェクト構成

### リポジトリ構成

- [メインリポジトリ](https://github.com/hiroi-sora/Umi-OCR)
- [プラグインリポジトリ](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows ランタイムリポジトリ](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux ランタイムリポジトリ](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### ランタイムレイアウト（上流の標準レイアウト）

`**` はこのメインリポジトリに含まれる内容を示します。

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

### このリポジトリスナップショットのソースツリー

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

## 前提条件

### エンドユーザー

| 項目 | 要件 |
| --- | --- |
| OS | Windows 7 x64+ または Linux x64 |
| CPU（推奨） | AVX 対応 x64 CPU（PaddleOCR ベースのプラグイン向け） |
| ランタイム（Windows 推奨） | Visual C++ ランタイム（互換性のため） |

### 開発者

- 次を参照してプラットフォーム向けランタイム設定を実施:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- このリポジトリには、pip ベースのセットアップに対応した `requirements.txt` や `pyproject.toml` は含まれていません。

## インストール

### 方法 A: ポータブル版（推奨）

1. `.7z` または自己解凍型 `.7z.exe` パッケージをダウンロード。
2. ファイルを展開。
3. `Umi-OCR.exe` を起動。

### 方法 B: Scoop（Windows）

```bash
scoop bucket add extras
```

RapidOCR 版（互換性優先）:

```bash
scoop install extras/umi-ocr
```

PaddleOCR 版（やや高速）:

```bash
scoop install extras/umi-ocr-paddle
```

2 つの版を同時にインストールしないでください（ショートカットの競合が起きる可能性があります）。必要ならプラグイン切り替えを使ってください。

### 方法 C: ランタイムリポジトリ経由のビルド/実行

ビルドとランタイム起動の手順は以下を参照。

- [Windows runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## リリースのダウンロード

| ミラー | リンク | 補足 |
| --- | --- | --- |
| Lanzou | [地域ミラー](https://hiroi-sora.lanzoul.com/s/umi-ocr) | 中国向けミラー |
| GitHub | [最新版](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | upstream の主要リリースページ |
| SourceForge | [ダウンロードミラー](https://sourceforge.net/projects/umi-ocr) | レガシーな代替チャネル |

## 使い方

### はじめに

- Umi-OCR はポータブルで、インストーラー不要。
- 展開後に `Umi-OCR.exe` を起動。
- 起動に失敗した場合は [トラブルシューティング](#トラブルシューティング) を確認。

### インターフェース言語

初回起動時、UI 言語はシステムロケールに従って自動選択されます。

手動変更: `Global Settings -> Language`

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### タブとワークフロー

- 必要なタブのみを開く。
- タブバー左上で常時最前面を切り替え。
- 右上で固定して誤って閉じないようにする。

### CLI の使い方

CLI マニュアル: [docs/README_CLI.md](docs/README_CLI.md)

基本コマンド:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

OCR コマンド:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

固定領域のスクリーンショット:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

QR コマンド:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

出力オプション:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### HTTP API の使い方

HTTP ドキュメント: [docs/http/README.md](docs/http/README.md)

主要エンドポイント:

| エンドポイント | 用途 |
| --- | --- |
| `/api/ocr/get_options` | OCR オプション |
| `/api/ocr` | OCR 実行 |
| `/api/doc/*` | 文書のオプション / アップロード / 結果 / ダウンロード |
| `/api/qrcode` | QR デコード |
| `/argv` | HTTP 経由の CLI ブリッジ |

注記: `Global Settings` では HTTP サービスを有効（既定）にしておく必要があります。LAN 接続が必要な場合のみローカル以外のホスト許可を行ってください。

## 設定

- ランタイム設定は `UmiOCR-data/.settings`（INI 形式）に保存されます。
- 設定を手動で編集した後は、以下で反映します。

```bash
umi-ocr --reload
```

- 起動/実行時の互換性状態は以下を含む場合があります。
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/`（ランタイムログ付きのバージョン）

## サンプル

### 例 1: パス指定でバッチ OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 例 2: 複数パスの QR 読み取り

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 例 3: 明示的なサイズで QR を生成

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### 例 4: 高度なモジュール呼び出し

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## API リファレンス

- CLI マニュアル: [docs/README_CLI.md](docs/README_CLI.md)
- HTTP API マニュアル: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- Document API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv ブリッジ: [docs/http/argv.md](docs/http/argv.md)

## 開発メモ

- エントリポイント:
  - `UmiOCR-data/main.py`（ランタイムブートストラップ）
  - `UmiOCR-data/py_src/run.py`（アプリ起動）
- UI スタック: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- コアサービス:
  - `py_src/server/*`（HTTP + コマンド転送）
  - `py_src/mission/*`（OCR / 文書 / QR タスクのキュー処理）
  - `py_src/ocr/*`（OCR 後処理と出力）
- 対応 OCR エンジン:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- ランタイム基盤: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## トラブルシューティング

詳細は以下を参照: [https://github.com/hiroi-sora/Umi-OCR/issues/447](https://github.com/hiroi-sora/Umi-OCR/issues/447)

クイックインデックス:

| 症状 | ジャンプ |
| --- | --- |
| `Py_Main()` が見つからない | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL コンテキストの作成に失敗 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 起動時にクラッシュする | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 初期化失敗（MKLDNN/AVX の示唆） | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| `api-ms-win-crt-runtime-l1-1-0.dll` が見つからない | [`Missing api-ms-win-crt-runtime-l1-1-0.dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- VC ランタイムをインストール: https://aka.ms/vs/17/release/vc_redist.x64.exe
- または代替として `UmiOCR-data/RUN_GUI.bat` で起動。
- 注意: `.bat` ランチャーには CLI 制御がなく、ショートカット自動化も制限があります。

### `Failed to create OpenGL context`

- ランタイムパッチをダウンロード: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 展開した DLL を `UmiOCR-data/site-packages/PySide2/` に配置。

### `Umi-OCR.exe has stopped working`

- 異なる Windows バージョン間で設定を再利用したときに発生しやすいです。
- `UmiOCR-data/.pre_settings` を削除して再試行。

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- CPU が AVX に非対応の可能性があります。
- RapidOCR 版を使うか、PaddleOCR プラグインを切り替えてください。
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- 旧式の未パッチ Windows 7（特に `KB2533623` が未適用）でよく発生します。
- 推奨対応: Windows Update を実行し、再起動。

### Crash while exporting searchable PDF

- Windows 7 更新不足（特に `KB4534310` と依存更新）が原因で起きやすいです。
- 推奨対応: Windows Update で不足している更新をすべて適用。

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- VC ランタイムをインストール: https://aka.ms/vs/17/release/vc_redist.x64.exe

### Manual Shortcut Placement

自動ショートカット作成が失敗した場合は手動で配置してください。

- スタートメニュー: `C:\ProgramData\Microsoft\Windows\Start Menu`
- スタートアップ: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## ローカリゼーション

このプロジェクトは Weblate を使った共同ローカリゼーションを採用しています。

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

このリポジトリ内の README 言語ファイル:

| 言語 | ファイル |
| --- | --- |

翻訳の貢献ありがとうございます:

| 翻訳者 | 寄稿言語 |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

誤りや抜けがある場合は、[こちらのディスカッション](https://github.com/hiroi-sora/Umi-OCR/discussions/449)に返信してください。

## ロードマップ

### 完了

- タブページアーキテクチャ。
- OCR API コントローラー。
- OCR ミッション / タスクコントローラー。
- ライト / ダーク対応のテーママネージャー。
- バッチ OCR。
- スクリーンショット OCR。
- ホットキー機構。
- システムトレイメニュー。
- テキストブロック後処理（レイアウト最適化）。
- エンジンのメモリクリア。
- 多言語 UI。
- コマンドラインモード。
- Windows 7 互換。
- Excel（CSV）出力フォーマット。
- `Esc` キーでスクリーンショット中断。
- 外部テーマファイル。
- フォント切り替え。
- ローディングアニメーション。
- 除外領域。
- QR コード認識。
- バッチ認識での画像プレビュー。
- PDF 認識。
- ローカル画像ビューアで画像を開く。 [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- 前回のスクリーンショット領域を再利用。 [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- 文書認識における Windows 7 互換性問題を修正。
- HTTP と CLI インターフェースでの QR 読み取り/作成サポート。 (#423)
- QR インターフェース文書。
- Linux への移植。
- HTTP 文書認識 API。

### 長期計画

以下の項目は予定案であり、開発中に変更される可能性があります。

- [ ] 基盤となるプラグイン機構のリファクタリング。
- [ ] オンライン OCR API プラグイン。
- [ ] 独立した数式認識プラグイン。
- [ ] LaTeX レンダリング付きの専用数式タブ。
- [ ] 更新チェック機能。
- [ ] レイアウト解析以外の追加後処理モジュール。
- [ ] キーユーザーインターフェース機能向けイベントトリガー。
- [ ] GPU ベースのオフライン OCR。
- [ ] 画像翻訳。
- [ ] オフライン翻訳。
- [ ] 固定領域 OCR。
- [ ] テーブル認識の Excel 出力。
- [ ] 履歴システム。
- [ ] macOS / Ubuntu など他プラットフォームへの互換拡張。

## 貢献

コントリビューションは歓迎します。

- バグ報告や機能要望は [Issues](https://github.com/hiroi-sora/Umi-OCR/issues) へ。
- アイデアは [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) で議論。
- 翻訳は [Weblate](https://hosted.weblate.org/engage/umi-ocr/) に参加。
- エンジン／プラグイン関連については [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins) も参照。

開発環境のセットアップについては、プラットフォーム別のランタイムリポジトリを参照してください。

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。

- [LICENSE](LICENSE)


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
