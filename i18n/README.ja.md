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
    <a href="#table-of-contents">使い方</a>
    <span> • </span>
    <a href="#download-releases">リリースのダウンロード</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">変更履歴</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">問題を報告</a>
  </h3>
</div>

<div align="center">
  <strong>無料・オープンソースのバッチ対応オフラインOCRソフトウェア</strong><br>
  <sub>Windows 7 x64 および Linux x64 に対応</sub>
</div>

## 概要

Umi-OCR は、オフライン処理・高スループットなバッチワークフロー・実用的な連携機能に注力した、デスクトップファーストの OCR ツールです。

- **無料**: すべてのコードがオープンソースで、無償で利用できます。
- **手軽**: 展開してそのまま実行でき、OCR の中核機能にネットワークは不要です。
- **高効率**: 複数言語対応のオフライン OCR エンジンを同梱しています。
- **柔軟**: GUI ワークフロー、コマンドライン制御、HTTP API を利用できます。
- **多機能**: スクリーンショット OCR、バッチ OCR、文書 OCR、QR 読み取り/生成、数式認識の導線を提供します。

| ✅ クイック情報 | 詳細 |
| --- | --- |
| 🧩 ライセンス | MIT |
| 🌐 ネットワーク要件 | OCR の主要ワークフローにネットワーク不要 |
| 💻 対応環境 | Windows 7 x64+ / Linux x64 |
| 🛠 利用モード | GUI, CLI, HTTP API |
| 🌍 翻訳 | Weblate ベースのコミュニティローカライズ |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## 目次

- [機能](#機能)
- [プロジェクト構成](#プロジェクト構成)
- [前提条件](#前提条件)
- [インストール](#インストール)
- [リリースのダウンロード](#リリースのダウンロード)
- [使い方](#使い方)
- [設定](#設定)
- [使用例](#使用例)
- [API リファレンス](#api-リファレンス)
- [開発メモ](#開発メモ)
- [トラブルシューティング](#トラブルシューティング)
- [ローカライズ](#ローカライズ)
- [ロードマップ](#ロードマップ)
- [コントリビューション](#コントリビューション)
- [サポート](#サポート)
- [ライセンス](#ライセンス)

## 機能

### スクリーンショット OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- Screenshot OCR タブを開いた後、スクリーンショット用ショートカットで OCR を実行できます。
- 左パネルでは画像プレビュー上で直接テキスト選択できます。
- 右パネルでは認識履歴の編集と複数レコードのコピーに対応しています。
- クリップボードから貼り付けた画像にも対応しています。
- 数式認識の参考: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### テキスト後処理（レイアウト解析）

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

OCR ブロックを並べ替えて読みやすさを高める、組み込みスキームを利用できます。

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (コードスニペットに有用)
- `No post-processing` (生の OCR 出力)

選択した OCR エンジンモデルが対応していれば、これらのスキームは横書きと縦書き（右から左）レイアウトを処理できます。

### バッチ OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 入力形式: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 出力形式: `txt, jsonl, md, csv(Excel)`
- スクリーンショット OCR のテキスト後処理ルールを利用できます。
- UI ワークフローでは実用上のタスク件数上限はありません（1 回で数百枚の画像を処理可能）。
- タスク完了後の自動シャットダウン/スリープに対応しています。
- 超高解像度画像では `OCR settings -> image side limit` を調整してください。

#### 除外領域

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- バッチ OCR 中に固定の透かし/ロゴ文字列を除外できます。
- 除外領域エディターでは、右クリックで複数の矩形を描画できます。
- より堅牢にするため、対象透かしよりやや大きめの矩形を描画してください。
- 除外はブロック単位です（領域内のテキストブロックは無視されます）。

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 文書 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 入力形式: `pdf, xps, epub, mobi, fb2, cbz`
- 埋め込みテキストがある場合は抽出し、ない場合はスキャンページを OCR します。
- 検索可能なレイヤー付き PDF を出力できます。
- 除外領域（ヘッダー/フッター向け）に対応しています。
- タスク完了後の自動シャットダウン/スリープに対応しています。

### QR コード

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

読み取りモード:

- スクリーンショット、貼り付け、ローカル画像のドラッグでデコードできます。
- 1 枚の画像内にある複数コードの読み取りに対応しています。
- 19 形式に対応:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

生成モード:

- テキストから QR/バーコード画像を生成できます。
- 形式選択と誤り訂正設定に対応しています。

### 全体設定

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- ショートカット追加と起動動作の設定が可能です。
- UI 言語を切り替えできます。
- テーマ（ライト/ダーク）を切り替えできます。
- フォントと UI スケーリングを設定できます。
- OCR プラグインを切り替えできます。
- GPU アクセラレーションでちらつきや UI ずれが起きる場合は `Interface and Appearance -> Renderer` でレンダラーを変更してください。

## プロジェクト構成

### リポジトリ関係

- [メインリポジトリ](https://github.com/hiroi-sora/Umi-OCR)
- [プラグインリポジトリ](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows ランタイムリポジトリ](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux ランタイムリポジトリ](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### ランタイム構成（公式アップストリーム構成）

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

### このリポジトリスナップショット内のソースツリー

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
| ランタイム（Windows 推奨） | 互換性向上のため Visual C++ ランタイム |

### 開発者

- 次のランタイムセットアップ手順を読み、従ってください:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- このリポジトリには、`pip` で直接セットアップするための独立した `requirements.txt` や `pyproject.toml` は用意されていません。

## インストール

### オプション A: ポータブルリリースパッケージ（推奨）

1. `.7z` または自己解凍形式 `.7z.exe` パッケージをダウンロードします。
2. ファイルを展開します。
3. `Umi-OCR.exe` を起動します。

### オプション B: Scoop（Windows）

```bash
scoop bucket add extras
```

RapidOCR 版（互換性重視）:

```bash
scoop install extras/umi-ocr
```

PaddleOCR 版（やや高速）:

```bash
scoop install extras/umi-ocr-paddle
```

両バリアントを同時にインストールしないでください（ショートカット競合の可能性があります）。必要に応じてプラグイン切り替えを利用してください。

### オプション C: ランタイムリポジトリ経由でビルド/実行

次のビルド/ランタイム初期化手順に従ってください:

- [Windows ランタイムセットアップ](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux ランタイムセットアップ](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## リリースのダウンロード

| ミラー | リンク | 備考 |
| --- | --- | --- |
| Lanzou | https://hiroi-sora.lanzoul.com/s/umi-ocr | 地域向けミラー |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | 主要アップストリーム配布ページ |
| SourceForge | https://sourceforge.net/projects/umi-ocr | 代替ダウンロードミラー |

## 使い方

### はじめに

- Umi-OCR はポータブルで、インストーラーは不要です。
- 展開後に `Umi-OCR.exe` を起動してください。
- 起動に失敗する場合は [トラブルシューティング](#トラブルシューティング) を参照してください。

### インターフェース言語

初回起動時、UI 言語はシステムロケールに基づいて自動選択されます。

手動切り替え: `Global Settings -> Language`。

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### タブとワークフロー

- ワークフローに必要なタブだけを開いてください。
- タブバー左上から最前面表示を切り替えできます。
- 誤って閉じるのを防ぐため、右上からタブをロックできます。

### コマンドライン利用

CLI マニュアル: [docs/README_CLI.md](docs/README_CLI.md)

基本操作:

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

固定領域でスクリーンショット:

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

### HTTP API 利用

HTTP ドキュメント: [docs/http/README.md](docs/http/README.md)

主なエンドポイント:

| エンドポイント | 用途 |
| --- | --- |
| `/api/ocr/get_options` | OCR オプション |
| `/api/ocr` | OCR 実行 |
| `/api/doc/*` | 文書オプション/アップロード/結果/ダウンロード |
| `/api/qrcode` | QR デコード |
| `/argv` | HTTP 経由 CLI ブリッジ |

注: `Global Settings` で HTTP サービスを有効のままにしておく必要があります（既定値は有効）。LAN アクセスが必要な場合を除き、ローカル専用ホストを使用してください。

## 設定

- ランタイム設定は `UmiOCR-data/.settings`（INI 形式）に保存されます。
- 設定を手動編集した後は、次で反映してください:

```bash
umi-ocr --reload
```

- 起動/実行時の互換状態には、次も関係する場合があります:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/`（ランタイムログ対応版の場合）

## 使用例

### 例1: パス指定でバッチ OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 例2: 複数パスから QR を読み取り

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 例3: サイズ指定で QR を生成

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### 例4: 高度なモジュール呼び出し

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## API リファレンス

- コマンドラインマニュアル: [docs/README_CLI.md](docs/README_CLI.md)
- HTTP API マニュアル: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- 文書 API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv ブリッジ: [docs/http/argv.md](docs/http/argv.md)

## 開発メモ

- エントリーポイント:
  - `UmiOCR-data/main.py`（ランタイム起動）
  - `UmiOCR-data/py_src/run.py`（アプリケーション起動）
- UI スタック: PySide2 + QML（`UmiOCR-data/qt_res/qml`）。
- コアサービス:
  - HTTP + コマンド転送は `py_src/server/*`
  - キュー実行の OCR/Doc/QR タスクは `py_src/mission/*`
  - OCR 後処理と出力は `py_src/ocr/*`
- エコシステムで対応する OCR エンジン:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- ランタイムフレームワーク: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## トラブルシューティング

トラブルシューティングの完全版: https://github.com/hiroi-sora/Umi-OCR/issues/447

クイック索引:

| 症状 | ジャンプ |
| --- | --- |
| `Py_Main()` が見つからない | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL コンテキスト作成に失敗 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 起動時にアプリがクラッシュする | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 初期化失敗 | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| `api-ms-win-crt-runtime-l1-1-0.dll` が不足 | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- VC ランタイムをインストール: https://aka.ms/vs/17/release/vc_redist.x64.exe
- またはフォールバック `UmiOCR-data/RUN_GUI.bat` で起動してください。
- 注: `.bat` ランチャーには制限があります（CLI 制御不可、ショートカット自動化が限定的）。

### `Failed to create OpenGL context`

- ランタイムパッチをダウンロード: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 展開した DLL を `UmiOCR-data/site-packages/PySide2/` に配置します。

### `Umi-OCR.exe has stopped working`

- 異なる Windows バージョン間で設定を流用した場合によく発生します。
- `UmiOCR-data/.pre_settings` を削除して再試行してください。

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- CPU が AVX 非対応の可能性があります。
- RapidOCR 版を使うか、PaddleOCR プラグイン以外へ切り替えてください:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### `OSError` を伴う黒いコンソール（プログラムが見つからない）

- 更新未適用の初期 Windows 7 で起きやすい問題です（特に `KB2533623` 不足）。
- 推奨対応: Windows Update を完全実行し、再起動してください。

### 検索可能 PDF のエクスポート中にクラッシュする

- Windows 7 の更新不足（特に `KB4534310` および依存更新）が原因のことが多いです。
- 推奨対応: Windows Update で不足している更新をすべて適用してください。

### `api-ms-win-crt-runtime-l1-1-0.dll` が不足

- VC ランタイムをインストール: https://aka.ms/vs/17/release/vc_redist.x64.exe

### ショートカットを手動配置する

ショートカット自動作成に失敗する場合は、手動で配置してください:

- スタートメニュー: `C:\ProgramData\Microsoft\Windows\Start Menu`
- スタートアップ: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## ローカライズ

このプロジェクトは Weblate を使って共同ローカライズを行っています:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

このリポジトリ内の README 言語ファイル:

| 言語 | ファイル |
| --- | --- |

翻訳者の皆さまに感謝します:

| 翻訳者 | 貢献言語 |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

誤りや抜けがあれば、[このディスカッション](https://github.com/hiroi-sora/Umi-OCR/discussions/449) に返信してください。

## ロードマップ

### 完了済み

- タブページ構成。
- OCR API コントローラー。
- OCR ミッション/タスクコントローラー。
- ライト/ダーク対応テーママネージャー。
- バッチ OCR。
- スクリーンショット OCR。
- ホットキー機構。
- システムトレイメニュー。
- テキストブロック後処理（レイアウト最適化）。
- エンジンメモリクリーンアップ。
- 多言語 UI。
- コマンドラインモード。
- Windows 7 互換性。
- Excel（CSV）出力形式。
- スクリーンショット時の `Esc` 中断。
- 外部テーマファイル。
- フォント切り替え。
- ローディングアニメーション。
- 除外領域。
- QR コード認識。
- バッチ認識での画像プレビュー。
- PDF 認識。
- ローカル画像ビューアーで画像を開く。[#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- 直前のスクリーンショット領域を再利用。[#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- 文書認識における Windows 7 互換性問題を修正。
- HTTP/CLI インターフェースでの QR 読み取り/生成対応。(#423)
- QR インターフェース文書。
- Linux プラットフォーム移行。
- HTTP 文書認識 API。

### 長期計画

以下は構想段階の項目であり、開発中に変更される可能性があります:

- [ ] 基盤プラグイン機構のリファクタリング。
- [ ] オンライン OCR API プラグイン。
- [ ] 独立した数式認識プラグイン。
- [ ] LaTeX レンダリング対応の数式専用タブ。
- [ ] 更新チェック機構。
- [ ] レイアウト解析以外の追加後処理モジュール。
- [ ] 主要インターフェース機能向けイベントトリガー。
- [ ] GPU ベースのオフライン OCR。
- [ ] 画像翻訳。
- [ ] オフライン翻訳。
- [ ] 固定領域 OCR。
- [ ] 表認識から Excel 出力。
- [ ] 履歴システム。
- [ ] macOS/Ubuntu などへの対応拡張。

## コントリビューション

コントリビューションを歓迎します。

- バグ報告や機能要望は [Issues](https://github.com/hiroi-sora/Umi-OCR/issues) へ。
- アイデアの議論は [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions) へ。
- 翻訳への参加は [Weblate](https://hosted.weblate.org/engage/umi-ocr/) へ。
- エンジン/プラグイン関連は [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins) も参照してください。

開発環境のセットアップは、以下のランタイムリポジトリ手順に従ってください:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## サポート

Umi-OCR は主に [hiroi-sora](https://github.com/hiroi-sora) が空き時間に開発・保守しています。

このプロジェクトが役立った場合、スポンサー支援をご検討いただけると助かります:

- Afdian (CN): https://afdian.com/a/hiroi-sora

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## ライセンス

このプロジェクトは MIT License の下で提供されています。

- [LICENSE](LICENSE)
