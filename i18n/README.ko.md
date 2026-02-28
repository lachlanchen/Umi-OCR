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
    <a href="#목차">사용법</a>
    <span> • </span>
    <a href="#download-releases">릴리스 다운로드</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">변경 로그</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">이슈 제보</a>
  </h3>
</div>

<div align="center">
  <strong>무료, 오픈 소스 배치 오프라인 OCR 소프트웨어</strong><br>
  <sub>Windows 7 x64 및 Linux x64 호환</sub>
</div>

## 개요

Umi-OCR은 오프라인 처리, 대량 배치 워크플로, 그리고 실용적인 연동 기능에 초점을 둔 데스크톱 중심 OCR 도구입니다.

- **무료**: 모든 코드는 오픈 소스이며 자유롭게 사용할 수 있습니다.
- **편리함**: 로컬에서 바로 실행되며 핵심 OCR에 네트워크 의존이 없습니다.
- **효율성**: 다국어를 지원하는 오프라인 OCR 엔진을 기본 제공합니다.
- **유연성**: GUI 워크플로, 명령줄 제어, HTTP API를 지원합니다.
- **기능 풍부**: 스크린샷 OCR, 배치 OCR, 문서 OCR, QR 코드 읽기/생성, 수식 인식 진입점.

| ✅ 핵심 정보 | 세부 내용 |
| --- | --- |
| 🧩 라이선스 | MIT |
| 🌐 네트워크 요구사항 | 핵심 OCR 워크플로에는 네트워크 불필요 |
| 💻 플랫폼 | Windows 7 x64+ / Linux x64 |
| 🛠 사용 모드 | GUI, CLI, HTTP API |
| 🌍 번역 | Weblate 기반 커뮤니티 현지화 |

### 실무형 워크플로에 맞춤

| 워크플로 | 핵심 기능 |
| --- | --- |
| 스크린샷 처리 | 실시간 캡처에서 바로 자르기, 선택, 전사 |
| 배치 처리 | 폴더를 처리하고 후처리를 튜닝해 구조화 텍스트로 내보내기 |
| 문서 OCR | 스캔 문서를 OCR 처리해 검색 가능한 계층형 PDF 생성 |
| QR 처리 | 여러 코드를 디코딩하고 QR/바코드 자산을 생성 |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## 목차

- [기능](#기능)
- [프로젝트 구조](#프로젝트-구조)
- [사전 요구사항](#사전-요구사항)
- [설치](#설치)
- [릴리스 다운로드](#릴리스-다운로드)
- [사용법](#사용법)
- [설정](#설정)
- [예제](#예제)
- [API 레퍼런스](#api-레퍼런스)
- [개발 노트](#개발-노트)
- [문제 해결](#문제-해결)
- [현지화](#현지화)
- [로드맵](#로드맵)
- [기여](#기여)
- [Support](#support)
- [라이선스](#라이선스)

## 기능

### 스크린샷 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- 스크린샷 OCR 탭을 연 뒤 단축키로 OCR을 실행할 수 있습니다.
- 좌측 패널에서 이미지 미리보기에서 텍스트를 직접 선택할 수 있습니다.
- 우측 패널은 편집 가능한 인식 이력과 다중 기록 복사를 지원합니다.
- 클립보드에 붙여 넣은 이미지를 지원합니다.
- 수식 인식 참고: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### 텍스트 후처리 (레이아웃 파싱)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

내장 스킴을 통해 OCR 블록 순서를 재배열하고 가독성을 개선합니다:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (코드 조각에 유용)
- `No post-processing` (원본 OCR 출력)

선택한 OCR 엔진 모델이 지원하면 위 스킴은 가로/세로(우→좌) 레이아웃도 처리합니다.

### 배치 OCR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- 입력 형식: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- 출력 형식: `txt, jsonl, md, csv(Excel)`
- 스크린샷 OCR의 텍스트 후처리 규칙을 지원합니다.
- UI 워크플로 기준으로 작업 수 제한이 거의 없으며(1회 실행 시 수백 장 처리 지원).
- 작업 완료 후 자동 종료/절전 동작을 지원합니다.
- 초대형 이미지는 `OCR settings -> image side limit`를 조정하세요.

#### 제외 영역

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- 배치 OCR 시 반복적으로 나타나는 워터마크/로고 텍스트를 제외합니다.
- 제외 영역 편집기에서 마우스 오른쪽 버튼으로 여러 사각형을 그립니다.
- 안정성을 높이려면 대상 워터마크 영역보다 큰 사각형으로 지정합니다.
- 제외 동작은 블록 단위입니다(영역 내부의 텍스트 블록을 무시).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### 문서 OCR

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- 입력 형식: `pdf, xps, epub, mobi, fb2, cbz`
- 내장 텍스트가 있으면 추출하고, 없으면 스캔 페이지에 OCR을 수행합니다.
- 검색 가능한 계층형 PDF로 내보냅니다.
- 제외 영역(헤더/푸터 등)을 지원합니다.
- 작업 완료 후 자동 종료/절전을 지원합니다.

### QR 코드

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

읽기 모드:

- 스크린샷, 붙여넣기, 로컬 이미지 드래그로 디코딩 가능합니다.
- 한 이미지에서 여러 코드를 지원합니다.
- 19개 형식을 지원합니다:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

생성 모드:

- 텍스트에서 QR/바코드 이미지를 생성합니다.
- 형식 선택 및 오류 정정 설정을 지원합니다.

### 전역 설정

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- 단축키를 추가하고 시작 동작을 설정합니다.
- UI 언어 전환.
- 테마 전환(라이트/다크 변형).
- 폰트와 UI 배율을 설정.
- OCR 플러그인 전환.
- GPU 가속으로 깜빡임이나 오프셋이 생기면 렌더러를 변경합니다(`Interface and Appearance -> Renderer`).

## 프로젝트 구조

### 저장소 관계

- [메인 저장소](https://github.com/hiroi-sora/Umi-OCR)
- [플러그인 저장소](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows 런타임 저장소](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 런타임 저장소](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### 런타임 레이아웃 (정식 업스트림 레이아웃)

`**`는 이 메인 저장소에 포함된 콘텐츠를 뜻합니다.

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

### 이 저장소 스냅샷의 소스 트리

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

## 사전 요구사항

### 최종 사용자

| 항목 | 요구사항 |
| --- | --- |
| 운영체제 | Windows 7 x64+ 또는 Linux x64 |
| CPU (권장) | x64 CPU with AVX 지원 (PaddleOCR 기반 플러그인용) |
| 런타임 (Windows 권장) | 호환성을 위한 Visual C++ 런타임 |

### 개발자

- 다음 저장소의 플랫폼 런타임 설정을 읽고 따르세요:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- 이 저장소는 직접 `pip` 기반 설정을 위한 독립 `requirements.txt` 또는 `pyproject.toml`을 제공하지 않습니다.

## 설치

### 옵션 A: 포터블 릴리스 패키지 (권장)

1. `.7z` 또는 자동 압축 해제형 `.7z.exe` 패키지를 다운로드합니다.
2. 파일을 추출합니다.
3. `Umi-OCR.exe`를 실행합니다.

### 옵션 B: Scoop (Windows)

```bash
scoop bucket add extras
```

RapidOCR 변형(호환성 우수):

```bash
scoop install extras/umi-ocr
```

PaddleOCR 변형(조금 더 빠름):

```bash
scoop install extras/umi-ocr-paddle
```

두 변형을 동시에 설치하지 마세요(바로가기 충돌이 발생할 수 있습니다). 필요한 경우 플러그인 전환을 사용하세요.

### 옵션 C: 런타임 저장소로 빌드/실행

다음의 빌드/런타임 부트스트랩 안내를 따르세요:

- [Windows 런타임 설정](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux 런타임 설정](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## 릴리스 다운로드

| 미러 | 링크 | 비고 |
| --- | --- | --- |
| Lanzou | [지역 미러](https://hiroi-sora.lanzoul.com/s/umi-ocr) | 중국 지역 미러 |
| GitHub | [최신 릴리스](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | 기본 업스트림 릴리스 페이지 |
| SourceForge | [다운로드 미러](https://sourceforge.net/projects/umi-ocr) | 레거시 대체 채널 |

## 사용법

### 시작하기

- Umi-OCR은 포터블 방식이며 설치 프로그램이 필요 없습니다.
- 압축을 푼 뒤 `Umi-OCR.exe`를 실행합니다.
- 시작이 실패하면 [문제 해결](#문제-해결)을 참고하세요.

### 인터페이스 언어

첫 실행 시 UI 언어가 시스템 로케일에 따라 자동 선택됩니다.

수동 전환: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### 탭과 워크플로

- 워크플로에 필요한 탭만 엽니다.
- 탭 바 왼쪽 상단에서 항상 위 상태를 토글할 수 있습니다.
- 탭 바 오른쪽 상단에서 탭 잠금을 설정해 실수로 닫히는 것을 방지합니다.

### 명령줄 사용

CLI 매뉴얼: [docs/README_CLI.md](docs/README_CLI.md)

기본 제어:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

OCR 명령:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

고정 영역 스크린샷:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

QR 명령:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

출력 옵션:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### HTTP API 사용

HTTP 문서: [docs/http/README.md](docs/http/README.md)

핵심 엔드포인트:

| 엔드포인트 | 용도 |
| --- | --- |
| `/api/ocr/get_options` | OCR 설정 조회 |
| `/api/ocr` | OCR 실행 |
| `/api/doc/*` | 문서 옵션/업로드/결과/다운로드 |
| `/api/qrcode` | QR 디코딩 |
| `/argv` | HTTP 기반 CLI 브리지 |

참고: `Global Settings`에서 HTTP 서비스는 사용하도록 유지되어야 합니다(기본값). LAN 접근이 필요하지 않다면 로컬 전용 호스트를 사용하세요.

## 설정

- 런타임 설정은 `UmiOCR-data/.settings`(INI 형식)에 저장됩니다.
- 설정을 수동으로 편집한 뒤에는 다음으로 적용하세요:

```bash
umi-ocr --reload
```

- 일부 시작/런타임 호환 상태는 다음 항목과도 관련될 수 있습니다:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (런타임 로깅이 있는 버전)

## 예제

### 예제 1: 경로 기반 배치 OCR

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### 예제 2: 여러 경로에서 QR 읽기

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### 예제 3: 크기 지정으로 QR 생성

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### 예제 4: 고급 모듈 호출

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## API 레퍼런스

- 명령줄 매뉴얼: [docs/README_CLI.md](docs/README_CLI.md)
- HTTP API 매뉴얼: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- 문서 API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv 브리지: [docs/http/argv.md](docs/http/argv.md)

## 개발 노트

- 진입점:
  - `UmiOCR-data/main.py` (런타임 부트스트랩)
  - `UmiOCR-data/py_src/run.py` (애플리케이션 시작)
- UI 스택: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- 핵심 서비스:
  - HTTP + 명령 전송: `py_src/server/*`
  - 큐 기반 OCR/문서/QR 작업: `py_src/mission/*`
  - OCR 후처리 및 출력: `py_src/ocr/*`
- OCR 엔진 생태계 지원:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- 런타임 프레임워크: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## 문제 해결

전체 문제 해결 상세: https://github.com/hiroi-sora/Umi-OCR/issues/447

빠른 색인:

| 증상 | 바로가기 |
| --- | --- |
| `Py_Main()`을 찾을 수 없음 | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL 컨텍스트 생성 실패 | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| 시작 시 앱 충돌 | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR 초기화 실패 | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| `api-ms-win-crt-runtime-l1-1-0.dll` 누락 | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- VC 런타임 설치: https://aka.ms/vs/17/release/vc_redist.x64.exe
- 또는 대체 실행기 `UmiOCR-data/RUN_GUI.bat`로 실행하세요.
- 참고: `.bat` 실행기는 제약이 있습니다(CLI 제어 불가, 단축키 자동화 제한).

### `Failed to create OpenGL context`

- 런타임 패치 다운로드: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- 압축 해제한 DLL을 `UmiOCR-data/site-packages/PySide2/`에 넣으세요.

### `Umi-OCR.exe has stopped working`

- 다른 Windows 버전 간 설정을 재사용한 뒤 자주 발생합니다.
- `UmiOCR-data/.pre_settings`를 제거하고 다시 시도하세요.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- CPU가 AVX를 지원하지 않을 수 있습니다.
- RapidOCR 변형을 사용하거나 PaddleOCR 플러그인에서 전환하세요:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### `OSError`가 표시되는 검은 콘솔 (프로그램을 찾을 수 없음)

- 초기 Windows 7 환경(특히 `KB2533623` 누락)에서 흔합니다.
- 권장 해결: Windows Update를 모두 적용한 뒤 재부팅하세요.

### 검색 가능한 PDF 내보내기 중 충돌

- 종종 Windows 7 업데이트 누락(`KB4534310` 및 의존성) 때문에 발생합니다.
- 권장 해결: Windows Update로 누락된 시스템 업데이트를 모두 설치하세요.

### `api-ms-win-crt-runtime-l1-1-0.dll` 누락

- VC 런타임 설치: https://aka.ms/vs/17/release/vc_redist.x64.exe

### 수동 바로가기 배치

자동 바로가기 생성이 실패하면 바로가기를 직접 배치하세요:

- 시작 메뉴: `C:\ProgramData\Microsoft\Windows\Start Menu`
- 시작프로그램: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## 현지화

이 프로젝트는 협업 현지화를 위해 Weblate를 사용합니다:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

이 저장소의 README 언어 파일:

| Language | File |
| --- | --- |

감사합니다:

| 기여자 | 기여 언어 |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

오류나 누락이 있다면 [이 토론](https://github.com/hiroi-sora/Umi-OCR/discussions/449)에서 알려주세요.

## 로드맵

### 완료됨

- 탭 페이지 아키텍처.
- OCR API 컨트롤러.
- OCR 미션/작업 컨트롤러.
- 라이트/다크를 지원하는 테마 매니저.
- 배치 OCR.
- 스크린샷 OCR.
- 단축키 메커니즘.
- 시스템 트레이 메뉴.
- 텍스트 블록 후처리(레이아웃 최적화).
- 엔진 메모리 정리.
- 다국어 UI.
- 명령줄 모드.
- Windows 7 호환성.
- Excel (CSV) 출력 형식.
- 스크린샷에서 `Esc` 중단.
- 외부 테마 파일.
- 폰트 전환.
- 로딩 애니메이션.
- 제외 영역.
- QR 코드 인식.
- 배치 인식의 이미지 미리보기.
- PDF 인식.
- 로컬 이미지 뷰어로 이미지 열기. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- 이전 스크린샷 영역 반복. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- 문서 인식의 Windows 7 호환성 문제 수정.
- HTTP 및 CLI 인터페이스에서 QR 읽기/생성 지원. (#423)
- QR 인터페이스 문서.
- Linux 플랫폼 마이그레이션.
- HTTP 문서 인식 API.

### 장기 계획

다음 항목은 계획 아이디어이며 개발 과정에서 변경될 수 있습니다:

- [ ] 기반 플러그인 메커니즘 리팩터링.
- [ ] 온라인 OCR API 플러그인.
- [ ] 독립 수식 인식 플러그인.
- [ ] LaTeX 렌더링을 지원하는 전용 수식 탭.
- [ ] 업데이트 확인 메커니즘.
- [ ] 레이아웃 파싱 외의 추가 후처리 모듈.
- [ ] 주요 인터페이스 기능용 이벤트 트리거.
- [ ] GPU 기반 오프라인 OCR.
- [ ] 이미지 번역.
- [ ] 오프라인 번역.
- [ ] 고정 영역 OCR.
- [ ] 표 인식 후 Excel 출력.
- [ ] 히스토리 시스템.
- [ ] macOS/Ubuntu 등 플랫폼 호환성 확장.

## 기여

기여를 환영합니다.

- [Issues](https://github.com/hiroi-sora/Umi-OCR/issues)에서 버그 제보 또는 기능 요청.
- [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions)에서 아이디어 논의.
- [Weblate](https://hosted.weblate.org/engage/umi-ocr/)에서 번역 기여.
- 엔진/플러그인 작업은 [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)도 참고하세요.

개발 환경 설정은 플랫폼 런타임 저장소를 따르세요:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## 라이선스

이 프로젝트는 MIT License로 배포됩니다.

- [LICENSE](LICENSE)


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
