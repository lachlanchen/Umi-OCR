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
  <a href="#tai-ban-phat-hanh">
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
    <a href="#muc-luc">Cách dùng</a>
    <span> • </span>
    <a href="#tai-ban-phat-hanh">Tải bản phát hành</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">Nhật ký thay đổi</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">Báo lỗi</a>
  </h3>
</div>

<div align="center">
  <strong>Phần mềm OCR offline, mã nguồn mở, miễn phí, hỗ trợ xử lý hàng loạt</strong><br>
  <sub>Tương thích với Windows 7 x64 và Linux x64</sub>
</div>

## Tổng quan

Umi-OCR là công cụ OCR ưu tiên desktop, tập trung vào xử lý offline, luồng công việc hàng loạt hiệu năng cao và khả năng tích hợp thực tế.

- **Miễn phí**: Toàn bộ mã nguồn mở và dùng miễn phí.
- **Tiện lợi**: Giải nén và chạy cục bộ, OCR lõi không phụ thuộc mạng.
- **Hiệu quả**: Tích hợp sẵn các engine OCR offline hỗ trợ đa ngôn ngữ.
- **Linh hoạt**: Hỗ trợ quy trình GUI, điều khiển dòng lệnh và HTTP API.
- **Đầy đủ tính năng**: OCR ảnh chụp màn hình, OCR hàng loạt, OCR tài liệu, đọc/tạo mã QR, điểm vào nhận dạng công thức.

| ✅ Thông tin nhanh | Chi tiết |
| --- | --- |
| 🧩 Giấy phép | MIT |
| 🌐 Yêu cầu mạng | Không cần mạng cho các luồng OCR cốt lõi |
| 💻 Nền tảng | Windows 7 x64+ / Linux x64 |
| 🛠 Chế độ sử dụng | GUI, CLI, HTTP API |
| 🌍 Dịch thuật | Bản địa hóa cộng đồng qua Weblate |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## Mục lục

- [Tính năng](#tinh-nang)
- [Cấu trúc dự án](#cau-truc-du-an)
- [Điều kiện tiên quyết](#dieu-kien-tien-quyet)
- [Cài đặt](#cai-dat)
- [Tải bản phát hành](#tai-ban-phat-hanh)
- [Cách dùng](#cach-dung)
- [Cấu hình](#cau-hinh)
- [Ví dụ](#vi-du)
- [Tham chiếu API](#tham-chieu-api)
- [Ghi chú phát triển](#ghi-chu-phat-trien)
- [Khắc phục sự cố](#khac-phuc-su-co)
- [Bản địa hóa](#ban-dia-hoa)
- [Lộ trình](#lo-trinh)
- [Đóng góp](#dong-gop)
- [Hỗ trợ](#ho-tro)
- [Giấy phép](#giay-phep)

## Tính năng

### OCR ảnh chụp màn hình

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- Kích hoạt OCR bằng phím tắt chụp màn hình sau khi mở tab Screenshot OCR.
- Khung bên trái hỗ trợ chọn văn bản trực tiếp trong phần xem trước ảnh.
- Khung bên phải hỗ trợ chỉnh sửa lịch sử nhận dạng và sao chép nhiều bản ghi.
- Hỗ trợ dán ảnh từ clipboard.
- Tham khảo nhận dạng công thức: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### Hậu xử lý văn bản (phân tích bố cục)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

Các scheme tích hợp sẵn để sắp xếp lại khối OCR và cải thiện khả năng đọc:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (hữu ích cho đoạn mã)
- `No post-processing` (đầu ra OCR thô)

Các scheme này có thể xử lý bố cục ngang và dọc (phải sang trái) nếu model engine OCR đã chọn hỗ trợ.

### OCR hàng loạt

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- Định dạng đầu vào: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- Định dạng đầu ra: `txt, jsonl, md, csv(Excel)`
- Hỗ trợ các quy tắc hậu xử lý văn bản từ Screenshot OCR.
- Không có giới hạn thực tế về số tác vụ trong luồng UI (hỗ trợ hàng trăm ảnh mỗi lần chạy).
- Hỗ trợ tự động tắt máy/ngủ sau khi hoàn tất tác vụ.
- Với ảnh siêu lớn, điều chỉnh `OCR settings -> image side limit`.

#### Vùng bỏ qua

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- Loại trừ watermark/logo cố định khi OCR hàng loạt.
- Vẽ nhiều hình chữ nhật bằng nút chuột phải trong trình chỉnh sửa Ignore Region.
- Vẽ hình chữ nhật lớn hơn vùng watermark mục tiêu để tăng độ ổn định.
- Cơ chế bỏ qua theo khối (khối văn bản nằm trong vùng sẽ bị bỏ qua).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### OCR tài liệu

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- Định dạng đầu vào: `pdf, xps, epub, mobi, fb2, cbz`
- Trích xuất văn bản nhúng khi có, hoặc OCR các trang scan.
- Xuất PDF có lớp văn bản để tìm kiếm.
- Hỗ trợ vùng bỏ qua (cho header/footer).
- Hỗ trợ tự động tắt máy/ngủ sau khi hoàn tất tác vụ.

### Mã QR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

Chế độ đọc:

- Chụp màn hình, dán hoặc kéo thả ảnh cục bộ để giải mã.
- Hỗ trợ nhiều mã trong một ảnh.
- Hỗ trợ 19 định dạng:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

Chế độ tạo:

- Tạo ảnh QR/mã vạch từ văn bản.
- Hỗ trợ chọn định dạng và thiết lập sửa lỗi.

### Thiết lập toàn cục

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- Thêm phím tắt và cấu hình hành vi khởi động.
- Chuyển ngôn ngữ giao diện.
- Chuyển theme (biến thể sáng/tối).
- Cấu hình font và tỉ lệ giao diện.
- Chuyển plugin OCR.
- Đổi renderer (`Interface and Appearance -> Renderer`) khi tăng tốc GPU gây nhấp nháy hoặc lệch UI.

## Cấu trúc dự án

### Quan hệ repository

- [Main repository](https://github.com/hiroi-sora/Umi-OCR)
- [Plugin repository](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Windows runtime repository](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime repository](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### Bố cục runtime (bố cục upstream chuẩn)

`**` nghĩa là nội dung có trong repository chính này.

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

### Cây mã nguồn trong snapshot repository này

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

## Điều kiện tiên quyết

### Người dùng cuối

| Mục | Yêu cầu |
| --- | --- |
| Hệ điều hành | Windows 7 x64+ hoặc Linux x64 |
| CPU (khuyến nghị) | CPU x64 có hỗ trợ AVX (cho plugin dựa trên PaddleOCR) |
| Runtime (Windows khuyến nghị) | Visual C++ runtime để tương thích |

### Nhà phát triển

- Đọc và làm theo hướng dẫn thiết lập runtime theo nền tảng tại:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- Repository này không cung cấp `requirements.txt` hoặc `pyproject.toml` độc lập cho thiết lập pip trực tiếp.

## Cài đặt

### Tùy chọn A: Gói phát hành portable (khuyến nghị)

1. Tải gói `.7z` hoặc `.7z.exe` tự giải nén.
2. Giải nén tệp.
3. Chạy `Umi-OCR.exe`.

### Tùy chọn B: Scoop (Windows)

```bash
scoop bucket add extras
```

Biến thể RapidOCR (tương thích tốt hơn):

```bash
scoop install extras/umi-ocr
```

Biến thể PaddleOCR (nhanh hơn một chút):

```bash
scoop install extras/umi-ocr-paddle
```

Không cài đồng thời cả hai biến thể (có thể xung đột shortcut). Hãy dùng chuyển đổi plugin khi cần.

### Tùy chọn C: Build/Run qua runtime repositories

Làm theo hướng dẫn build/bootstrap runtime từ:

- [Windows runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Linux runtime setup](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Tải bản phát hành

| Mirror | Liên kết | Ghi chú |
| --- | --- | --- |
| Lanzou | https://hiroi-sora.lanzoul.com/s/umi-ocr | Mirror theo khu vực |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | Trang phát hành upstream chính |
| SourceForge | https://sourceforge.net/projects/umi-ocr | Mirror tải xuống thay thế |

## Cách dùng

### Bắt đầu nhanh

- Umi-OCR là dạng portable; không cần trình cài đặt.
- Chạy `Umi-OCR.exe` sau khi giải nén.
- Nếu khởi động thất bại, xem [Khắc phục sự cố](#khac-phuc-su-co).

### Ngôn ngữ giao diện

Ở lần chạy đầu tiên, ngôn ngữ UI được tự động chọn theo locale hệ thống.

Để chuyển thủ công: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### Tab và luồng công việc

- Chỉ mở các tab cần thiết cho luồng làm việc.
- Bật/tắt luôn ở trên cùng từ góc trên trái thanh tab.
- Khóa tab từ góc trên phải để tránh đóng nhầm.

### Sử dụng dòng lệnh

Tài liệu CLI: [docs/README_CLI.md](docs/README_CLI.md)

Điều khiển cơ bản:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

Lệnh OCR:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

Chụp màn hình với vùng cố định:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

Lệnh QR:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

Tùy chọn đầu ra:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### Sử dụng HTTP API

Tài liệu HTTP: [docs/http/README.md](docs/http/README.md)

Các endpoint chính:

| Endpoint | Mục đích |
| --- | --- |
| `/api/ocr/get_options` | Tùy chọn OCR |
| `/api/ocr` | Thực thi OCR |
| `/api/doc/*` | Tùy chọn/tải lên/kết quả/tải xuống tài liệu |
| `/api/qrcode` | Giải mã QR |
| `/argv` | Cầu nối CLI qua HTTP |

Lưu ý: Trong `Global Settings`, dịch vụ HTTP phải được bật (mặc định). Chỉ dùng host cục bộ trừ khi cần truy cập qua LAN.

## Cấu hình

- Thiết lập runtime được lưu trong `UmiOCR-data/.settings` (định dạng INI).
- Sau khi chỉnh sửa config thủ công, áp dụng thay đổi bằng:

```bash
umi-ocr --reload
```

- Một số trạng thái tương thích khi khởi động/chạy cũng có thể liên quan đến:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (với các phiên bản có logging runtime)

## Ví dụ

### Ví dụ 1: OCR hàng loạt theo đường dẫn

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### Ví dụ 2: Đọc QR từ nhiều đường dẫn

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### Ví dụ 3: Tạo QR với kích thước chỉ định

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### Ví dụ 4: Gọi module nâng cao

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## Tham chiếu API

- Hướng dẫn dòng lệnh: [docs/README_CLI.md](docs/README_CLI.md)
- Hướng dẫn HTTP API: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- Document API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- Cầu nối HTTP argv: [docs/http/argv.md](docs/http/argv.md)

## Ghi chú phát triển

- Entry points:
  - `UmiOCR-data/main.py` (bootstrap runtime)
  - `UmiOCR-data/py_src/run.py` (khởi động ứng dụng)
- UI stack: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- Dịch vụ cốt lõi:
  - `py_src/server/*` cho HTTP + vận chuyển lệnh
  - `py_src/mission/*` cho hàng đợi tác vụ OCR/Doc/QR
  - `py_src/ocr/*` cho hậu xử lý OCR và đầu ra
- Các OCR engine được hệ sinh thái hỗ trợ:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- Khung runtime: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## Khắc phục sự cố

Xem chi tiết đầy đủ: https://github.com/hiroi-sora/Umi-OCR/issues/447

Mục lục nhanh:

| Triệu chứng | Đi tới |
| --- | --- |
| Không tìm thấy `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| Tạo OpenGL context thất bại | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| Ứng dụng crash khi khởi động | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / OCR init thất bại | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| Thiếu `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- Cài VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe
- Hoặc chạy bằng launcher dự phòng `UmiOCR-data/RUN_GUI.bat`.
- Lưu ý: launcher `.bat` có giới hạn (không điều khiển CLI được, tự động hóa phím tắt bị hạn chế).

### `Failed to create OpenGL context`

- Tải bản vá runtime: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- Chép DLL đã giải nén vào `UmiOCR-data/site-packages/PySide2/`.

### `Umi-OCR.exe has stopped working`

- Thường gặp sau khi dùng lại config giữa các phiên bản Windows khác nhau.
- Xóa `UmiOCR-data/.pre_settings` rồi thử lại.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- Nhiều khả năng CPU không hỗ trợ AVX.
- Dùng biến thể RapidOCR hoặc chuyển khỏi plugin PaddleOCR:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- Thường gặp trên Windows 7 đời đầu chưa vá đầy đủ (đặc biệt thiếu `KB2533623`).
- Cách khắc phục khuyến nghị: chạy Windows Update đầy đủ rồi khởi động lại.

### Crash while exporting searchable PDF

- Thường do thiếu bản cập nhật Windows 7 (đặc biệt `KB4534310` và các phụ thuộc).
- Cách khắc phục khuyến nghị: cài toàn bộ cập nhật hệ thống còn thiếu qua Windows Update.

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- Cài VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe

### Đặt shortcut thủ công

Nếu tự động tạo shortcut thất bại, hãy đặt shortcut thủ công:

- Start menu: `C:\ProgramData\Microsoft\Windows\Start Menu`
- Startup: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## Bản địa hóa

Dự án dùng Weblate cho bản địa hóa cộng tác:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

Các tệp README ngôn ngữ trong repository này:

| Ngôn ngữ | Tệp |
| --- | --- |

Cảm ơn tất cả các dịch giả:

| Dịch giả | Ngôn ngữ đã đóng góp |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

Nếu có lỗi hoặc thiếu sót, vui lòng phản hồi trong [thảo luận này](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

## Lộ trình

### Đã hoàn thành

- Kiến trúc trang tab.
- Bộ điều khiển OCR API.
- Bộ điều khiển nhiệm vụ/tác vụ OCR.
- Trình quản lý theme hỗ trợ sáng/tối.
- OCR hàng loạt.
- OCR ảnh chụp màn hình.
- Cơ chế hotkey.
- Menu khay hệ thống.
- Hậu xử lý khối văn bản (tối ưu bố cục).
- Dọn dẹp bộ nhớ engine.
- UI đa ngôn ngữ.
- Chế độ dòng lệnh.
- Tương thích Windows 7.
- Định dạng xuất Excel (CSV).
- Ngắt ảnh chụp bằng `Esc`.
- Tệp theme ngoài.
- Chuyển font.
- Hiệu ứng loading.
- Vùng bỏ qua.
- Nhận dạng mã QR.
- Xem trước ảnh trong nhận dạng hàng loạt.
- Nhận dạng PDF.
- Mở ảnh bằng trình xem ảnh cục bộ. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- Lặp lại vùng chụp màn hình trước đó. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- Sửa lỗi tương thích Windows 7 trong nhận dạng tài liệu.
- Hỗ trợ đọc/tạo QR trong giao diện HTTP và CLI. (#423)
- Tài liệu giao diện QR.
- Di chuyển sang nền tảng Linux.
- HTTP document-recognition API.

### Kế hoạch dài hạn

Các mục dưới đây là ý tưởng dự kiến và có thể thay đổi trong quá trình phát triển:

- [ ] Refactor cơ chế plugin nền tảng.
- [ ] Plugin OCR API trực tuyến.
- [ ] Plugin nhận dạng công thức độc lập.
- [ ] Tab công thức chuyên dụng có render LaTeX.
- [ ] Cơ chế kiểm tra cập nhật.
- [ ] Các module hậu xử lý bổ sung ngoài phân tích bố cục.
- [ ] Event trigger cho các chức năng giao diện chính.
- [ ] OCR offline dựa trên GPU.
- [ ] Dịch ảnh.
- [ ] Dịch offline.
- [ ] OCR vùng cố định.
- [ ] Nhận dạng bảng ra Excel.
- [ ] Hệ thống lịch sử.
- [ ] Mở rộng tương thích cho các nền tảng như macOS/Ubuntu.

## Đóng góp

Mọi đóng góp đều được chào đón.

- Báo lỗi hoặc đề xuất tính năng qua [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- Thảo luận ý tưởng trong [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- Đóng góp bản dịch qua [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- Với công việc về engine/plugin, xem thêm [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

Với thiết lập môi trường phát triển, làm theo các runtime repository theo nền tảng:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Hỗ trợ

Umi-OCR chủ yếu được phát triển và duy trì trong thời gian rảnh bởi [hiroi-sora](https://github.com/hiroi-sora).

Nếu dự án này hữu ích với bạn, rất cảm ơn sự tài trợ:

- Afdian (CN): https://afdian.com/a/hiroi-sora

## Lịch sử Star

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## Giấy phép

Dự án này được cấp phép theo MIT License.

- [LICENSE](LICENSE)
