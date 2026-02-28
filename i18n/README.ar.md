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
    <a href="#table-of-contents">الاستخدام</a>
    <span> • </span>
    <a href="#download-releases">تنزيل الإصدارات</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">سجل التغييرات</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">الإبلاغ عن المشاكل</a>
  </h3>
</div>

<div align="center">
  <strong>برنامج OCR مجاني ومفتوح المصدر، ويدعم المعالجة الدُفعية دون اتصال</strong><br>
  <sub>متوافق مع Windows 7 x64 و Linux x64</sub>
</div>

<a id="overview"></a>
## نظرة عامة

Umi-OCR أداة OCR موجّهة أساسًا لبيئة سطح المكتب، وتركّز على المعالجة دون اتصال، وسير العمل الدفعي عالي الإنتاجية، والتكاملات العملية.

- **مجاني**: كل الشيفرة مفتوحة المصدر ومجانية الاستخدام.
- **مريح**: فك الضغط وشغّل محليًا، دون اعتماد شبكي لعمليات OCR الأساسية.
- **فعّال**: محركات OCR دون اتصال مدمجة مع دعم متعدد اللغات.
- **مرن**: يدعم سير عمل GUI، والتحكم عبر سطر الأوامر، وواجهات HTTP API.
- **غني بالميزات**: OCR للقطات الشاشة، OCR دفعي، OCR للمستندات، قراءة/إنشاء QR، ومدخل للتعرّف على المعادلات.

| ✅ معلومات سريعة | التفاصيل |
| --- | --- |
| 🧩 الترخيص | MIT |
| 🌐 متطلبات الشبكة | لا حاجة للشبكة لعمليات OCR الأساسية |
| 💻 المنصات | Windows 7 x64+ / Linux x64 |
| 🛠 أوضاع الاستخدام | GUI، CLI، HTTP API |
| 🌍 الترجمة | توطين مجتمعي عبر Weblate |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Umi-OCR preview 1" style="width: 80%;"></p>

![Umi-OCR preview 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

<a id="table-of-contents"></a>
## جدول المحتويات

- [الميزات](#features)
- [هيكل المشروع](#project-structure)
- [المتطلبات المسبقة](#prerequisites)
- [التثبيت](#installation)
- [تنزيل الإصدارات](#download-releases)
- [الاستخدام](#usage)
- [الإعداد](#configuration)
- [أمثلة](#examples)
- [مراجع API](#api-references)
- [ملاحظات التطوير](#development-notes)
- [استكشاف الأخطاء وإصلاحها](#troubleshooting)
- [التوطين](#localization)
- [خارطة الطريق](#roadmap)
- [المساهمة](#contribution)
- [الدعم](#support)
- [الترخيص](#license)

<a id="features"></a>
## الميزات

### OCR لقطات الشاشة

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- فعّل OCR عبر اختصار لقطة الشاشة بعد فتح تبويب Screenshot OCR.
- اللوحة اليسرى تدعم تحديد النص مباشرة داخل معاينة الصورة.
- اللوحة اليمنى تدعم سجل تعرّف قابلًا للتحرير ونسخ سجلات متعددة.
- يدعم الصور الملصقة من الحافظة.
- مرجع التعرّف على المعادلات: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### المعالجة اللاحقة للنص (تحليل التخطيط)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

مخططات مدمجة لإعادة ترتيب كتل OCR وتحسين قابلية القراءة:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (مفيد لمقتطفات الشيفرة)
- `No post-processing` (ناتج OCR خام)

يمكن لهذه المخططات التعامل مع التخطيطات الأفقية والعمودية (من اليمين إلى اليسار) إذا كان نموذج محرك OCR المحدد يدعم ذلك.

### OCR الدُفعات

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- صيغ الإدخال: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- صيغ الإخراج: `txt, jsonl, md, csv(Excel)`
- يدعم قواعد المعالجة اللاحقة للنص من Screenshot OCR.
- لا يوجد حد عملي لعدد المهام في سير عمل الواجهة (مدعوم مئات الصور في التشغيل الواحد).
- يدعم الإيقاف/السكون التلقائي بعد اكتمال المهمة.
- للصور كبيرة الحجم جدًا، اضبط `OCR settings -> image side limit`.

#### مناطق التجاهل

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- استبعاد نصوص العلامة المائية/الشعار الثابتة أثناء OCR الدفعي.
- ارسم عدة مستطيلات بزر الفأرة الأيمن في محرر Ignore Region.
- ارسم مستطيلات أكبر قليلًا من منطقة العلامة المائية المستهدفة لزيادة المتانة.
- سلوك التجاهل قائم على الكتل (تُتجاهل كتلة النص الواقعة داخل المنطقة).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### OCR المستندات

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- صيغ الإدخال: `pdf, xps, epub, mobi, fb2, cbz`
- استخراج النص المضمن عند توفره أو تنفيذ OCR لصفحات ممسوحة ضوئيًا.
- تصدير ملفات PDF بطبقات نص قابلة للبحث.
- يدعم مناطق التجاهل (للرؤوس/التذييلات).
- يدعم الإيقاف/السكون التلقائي بعد اكتمال المهمة.

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

وضع القراءة:

- التقط لقطة شاشة، أو الصق، أو اسحب صورًا محلية لفك الترميز.
- يدعم عدة رموز في صورة واحدة.
- يدعم 19 صيغة:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

وضع الإنشاء:

- أنشئ صور QR/Barcode من النص.
- يدعم اختيار الصيغة وإعدادات تصحيح الخطأ.

### الإعدادات العامة

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- أضف اختصارات واضبط سلوك بدء التشغيل.
- بدّل لغة الواجهة.
- بدّل السمات (فاتح/داكن).
- اضبط الخط وتكبير الواجهة.
- بدّل إضافات OCR.
- غيّر المُصيّر (`Interface and Appearance -> Renderer`) عندما يسبب تسريع GPU وميضًا أو انحرافًا في الواجهة.

<a id="project-structure"></a>
## هيكل المشروع

### علاقات المستودعات

- [المستودع الرئيسي](https://github.com/hiroi-sora/Umi-OCR)
- [مستودع الإضافات](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [مستودع بيئة تشغيل Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [مستودع بيئة تشغيل Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### تخطيط بيئة التشغيل (تخطيط المصدر القياسي)

`**` يعني أن المحتوى ضمن هذا المستودع الرئيسي.

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

### شجرة المصدر في هذه اللقطة من المستودع

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
## المتطلبات المسبقة

### للمستخدمين النهائيين

| العنصر | المتطلب |
| --- | --- |
| نظام التشغيل | Windows 7 x64+ أو Linux x64 |
| المعالج (موصى به) | معالج x64 يدعم AVX (لإضافات PaddleOCR) |
| بيئة التشغيل (موصى بها لـ Windows) | Visual C++ runtime للتوافق |

### للمطورين

- اقرأ واتبع إعداد بيئة التشغيل حسب المنصة من:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- هذا المستودع لا يوفر `requirements.txt` أو `pyproject.toml` مستقلًا لإعداد مباشر عبر pip.

<a id="installation"></a>
## التثبيت

### الخيار A: حزمة الإصدار المحمولة (موصى به)

1. نزّل حزمة `.7z` أو الحزمة ذاتية الاستخراج `.7z.exe`.
2. فك الملفات.
3. شغّل `Umi-OCR.exe`.

### الخيار B: Scoop (Windows)

```bash
scoop bucket add extras
```

نسخة RapidOCR (توافق أفضل):

```bash
scoop install extras/umi-ocr
```

نسخة PaddleOCR (أسرع قليلًا):

```bash
scoop install extras/umi-ocr-paddle
```

لا تثبّت النسختين معًا في نفس الوقت (قد يحدث تعارض في الاختصارات). استخدم تبديل الإضافة عند الحاجة.

### الخيار C: البناء/التشغيل عبر مستودعات بيئة التشغيل

اتبع تعليمات التهيئة للبناء/التشغيل من:

- [إعداد بيئة Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [إعداد بيئة Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="download-releases"></a>
## تنزيل الإصدارات

| المرآة | الرابط | ملاحظات |
| --- | --- | --- |
| Lanzou | https://hiroi-sora.lanzoul.com/s/umi-ocr | مرآة إقليمية |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | صفحة الإصدار الرئيسية في المصدر |
| SourceForge | https://sourceforge.net/projects/umi-ocr | مرآة تنزيل بديلة |

<a id="usage"></a>
## الاستخدام

### البدء السريع

- Umi-OCR محمول؛ لا يتطلب مُثبّتًا.
- شغّل `Umi-OCR.exe` بعد فك الضغط.
- إذا فشل التشغيل، راجع [استكشاف الأخطاء وإصلاحها](#troubleshooting).

### لغة الواجهة

عند التشغيل الأول، تُحدَّد لغة الواجهة تلقائيًا بحسب إعدادات لغة النظام.

للتبديل اليدوي: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### علامات التبويب وسير العمل

- افتح علامات التبويب المطلوبة فقط لسير عملك.
- فعّل/عطّل وضع البقاء في الأعلى من الزاوية العلوية اليسرى لشريط التبويبات.
- اقفل علامات التبويب من الأعلى يمينًا لمنع الإغلاق العرضي.

### الاستخدام عبر سطر الأوامر

دليل CLI: [docs/README_CLI.md](docs/README_CLI.md)

أوامر التحكم الأساسية:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

أوامر OCR:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

لقطة شاشة بمنطقة ثابتة:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

أوامر QR:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

خيارات الإخراج:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### استخدام HTTP API

وثائق HTTP: [docs/http/README.md](docs/http/README.md)

النهايات الأساسية:

| Endpoint | الغرض |
| --- | --- |
| `/api/ocr/get_options` | خيارات OCR |
| `/api/ocr` | تنفيذ OCR |
| `/api/doc/*` | خيارات/رفع/نتائج/تنزيل المستند |
| `/api/qrcode` | فك ترميز QR |
| `/argv` | جسر CLI عبر HTTP |

ملاحظة: في `Global Settings`، يجب أن تبقى خدمة HTTP مفعّلة (افتراضيًا). استخدم مضيفًا محليًا فقط ما لم تكن بحاجة لوصول LAN.

<a id="configuration"></a>
## الإعداد

- تُخزَّن إعدادات بيئة التشغيل في `UmiOCR-data/.settings` (صيغة INI).
- بعد تعديل الإعداد يدويًا، طبّق التغييرات عبر:

```bash
umi-ocr --reload
```

- قد تتضمن حالة التوافق عند بدء التشغيل/وقت التشغيل أيضًا:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (للإصدارات التي تتضمن تسجيلًا وقت التشغيل)

<a id="examples"></a>
## أمثلة

### المثال 1: OCR دفعي عبر المسار

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### المثال 2: قراءة QR من مسارات متعددة

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### المثال 3: إنشاء QR بحجم محدد

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### المثال 4: استدعاء متقدم للوحدات

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

<a id="api-references"></a>
## مراجع API

- دليل سطر الأوامر: [docs/README_CLI.md](docs/README_CLI.md)
- دليل HTTP API: [docs/http/README.md](docs/http/README.md)
- OCR API: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- Document API: [docs/http/api_doc.md](docs/http/api_doc.md)
- QR API: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- HTTP argv bridge: [docs/http/argv.md](docs/http/argv.md)

<a id="development-notes"></a>
## ملاحظات التطوير

- نقاط الدخول:
  - `UmiOCR-data/main.py` (تهيئة بيئة التشغيل)
  - `UmiOCR-data/py_src/run.py` (بدء التطبيق)
- مكدس الواجهة: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- الخدمات الأساسية:
  - `py_src/server/*` للنقل عبر HTTP + الأوامر
  - `py_src/mission/*` لمهام OCR/Doc/QR ضمن قائمة انتظار
  - `py_src/ocr/*` للمعالجة اللاحقة وإخراجات OCR
- محركات OCR المدعومة ضمن المنظومة:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- إطار التشغيل: [PyStand (customized)](https://github.com/skywind3000/PyStand)

<a id="troubleshooting"></a>
## استكشاف الأخطاء وإصلاحها

لتفاصيل الاستكشاف الكاملة: https://github.com/hiroi-sora/Umi-OCR/issues/447

فهرس سريع:

| العَرَض | الانتقال |
| --- | --- |
| لا يمكن العثور على `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| فشل إنشاء سياق OpenGL | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| التطبيق يتعطل عند البدء | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / فشل تهيئة OCR | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| فقدان `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

<a id="cannot-find-py_main"></a>
### `Cannot find Py_Main()`

- ثبّت VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe
- أو شغّل عبر بديل `UmiOCR-data/RUN_GUI.bat`.
- ملاحظة: مُشغّل `.bat` له قيود (لا تحكم CLI، وأتمتة اختصارات محدودة).

<a id="failed-to-create-opengl-context"></a>
### `Failed to create OpenGL context`

- نزّل تصحيح بيئة التشغيل: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- ضع ملف DLL المستخرج في `UmiOCR-data/site-packages/PySide2/`.

<a id="umi-ocrexe-has-stopped-working"></a>
### `Umi-OCR.exe has stopped working`

- شائع بعد إعادة استخدام إعدادات بين إصدارات Windows مختلفة.
- احذف `UmiOCR-data/.pre_settings` ثم أعد المحاولة.

<a id="0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints"></a>
### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- غالبًا المعالج لا يدعم AVX.
- استخدم نسخة RapidOCR أو بدّل بعيدًا عن إضافة PaddleOCR:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- شائع على Windows 7 المبكر غير المحدث (خصوصًا مع غياب `KB2533623`).
- الحل الموصى به: شغّل Windows Update بالكامل ثم أعد التشغيل.

### Crash while exporting searchable PDF

- غالبًا بسبب فقدان تحديثات Windows 7 (خصوصًا `KB4534310` واعتماداته).
- الحل الموصى به: تثبيت جميع تحديثات النظام المفقودة عبر Windows Update.

<a id="missing-api-ms-win-crt-runtime-l1-1-0dll"></a>
### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- ثبّت VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe

### وضع الاختصارات يدويًا

إذا فشل إنشاء الاختصارات تلقائيًا، ضعها يدويًا:

- قائمة البدء: `C:\ProgramData\Microsoft\Windows\Start Menu`
- بدء التشغيل: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

<a id="localization"></a>
## التوطين

يستخدم هذا المشروع Weblate للتوطين التعاوني:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

ملفات README اللغوية في هذا المستودع:

| اللغة | الملف |
| --- | --- |

شكرًا لجميع المترجمين:

| المترجم | اللغات المساهمة |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

إذا كانت هناك أخطاء أو سهو، يُرجى الرد في [هذا النقاش](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

<a id="roadmap"></a>
## خارطة الطريق

### مكتمل

- بنية صفحات بعلامات تبويب.
- متحكم OCR API.
- متحكم مهام OCR.
- مدير سمات مع دعم الفاتح/الداكن.
- OCR دفعي.
- OCR لقطات الشاشة.
- آلية اختصارات.
- قائمة صينية النظام.
- معالجة لاحقة لكتل النص (تحسين التخطيط).
- تنظيف ذاكرة المحرك.
- واجهة متعددة اللغات.
- وضع سطر الأوامر.
- توافق Windows 7.
- صيغة إخراج Excel (CSV).
- إيقاف لقطة الشاشة عبر `Esc`.
- ملفات سمات خارجية.
- تبديل الخط.
- حركة تحميل.
- مناطق التجاهل.
- التعرّف على QR.
- معاينة الصورة في التعرّف الدفعي.
- التعرّف على PDF.
- فتح الصورة عبر عارض الصور المحلي. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- تكرار منطقة لقطة الشاشة السابقة. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- إصلاح مشكلة توافق Windows 7 في تعرّف المستندات.
- دعم قراءة/إنشاء QR في واجهتي HTTP وCLI. (#423)
- توثيق واجهة QR.
- الترحيل إلى منصة Linux.
- HTTP API للتعرّف على المستندات.

### خطط طويلة المدى

العناصر التالية أفكار مخطط لها وقد تتطور أثناء التطوير:

- [ ] إعادة هيكلة آلية الإضافات الأساسية.
- [ ] إضافة OCR عبر API على الإنترنت.
- [ ] إضافة مستقلة للتعرّف على المعادلات.
- [ ] تبويب مخصص للمعادلات مع عرض LaTeX.
- [ ] آلية للتحقق من التحديثات.
- [ ] وحدات معالجة لاحقة إضافية تتجاوز تحليل التخطيط.
- [ ] مُحفزات أحداث لوظائف الواجهة الرئيسية.
- [ ] OCR دون اتصال معتمد على GPU.
- [ ] ترجمة الصور.
- [ ] ترجمة دون اتصال.
- [ ] OCR لمنطقة ثابتة.
- [ ] التعرّف على الجداول مع إخراج Excel.
- [ ] نظام سجل/تاريخ.
- [ ] توسيع التوافق لمنصات مثل macOS/Ubuntu.

<a id="contribution"></a>
## المساهمة

نرحب بالمساهمات.

- أبلغ عن الأخطاء أو اطلب ميزات عبر [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- ناقش الأفكار في [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- ساهم في الترجمات عبر [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- لأعمال المحرك/الإضافات، راجع أيضًا [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

لإعداد بيئة التطوير، اتبع مستودعات بيئة التشغيل حسب المنصة:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="support"></a>
## الدعم

يتم تطوير Umi-OCR وصيانته بشكل رئيسي في أوقات الفراغ بواسطة [hiroi-sora](https://github.com/hiroi-sora).

إذا كان هذا المشروع مفيدًا لك، فالدعم محل تقدير:

- Afdian (CN): https://afdian.com/a/hiroi-sora

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

<a id="license"></a>
## الترخيص

هذا المشروع مرخّص بموجب ترخيص MIT.

- [LICENSE](LICENSE)
