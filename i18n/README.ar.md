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
  <strong>برنامج OCR مفتوح المصدر ومجاني لمعالجة الدفعات دون اتصال بالإنترنت</strong><br>
  <sub>متوافق مع Windows 7 x64 و Linux x64</sub>
</div>

<a id="overview"></a>
## النظرة العامة

Umi-OCR هو أداة OCR موجهة لبيئة سطح المكتب تركز على المعالجة دون اتصال، وسير العمل بالدفعات عالية الإنتاجية، والتكاملات العملية.

- **مجاني**: الكود كاملًا مفتوح المصدر ومتاح مجانًا.
- **مريح**: استخراج وتشغيل محليًا، دون اعتماد على الشبكة لوظائف OCR الأساسية.
- **فعال**: يضم محركات OCR دون اتصال مع دعم متعدد اللغات.
- **مرن**: يدعم سير عمل GUI وCLI وHTTP APIs.
- **غني بالمزايا**: OCR من لقطة الشاشة، OCR دفعي، OCR للمستندات، قراءة/إنشاء رموز QR، ونقطة دخول للتعرف على الصيغ.

| ✅ حقائق سريعة | التفاصيل |
| --- | --- |
| 🧩 الترخيص | MIT |
| 🌐 متطلبات الشبكة | لا تحتاج إلى شبكة لعمليات OCR الأساسية |
| 💻 المنصة | Windows 7 x64+ / Linux x64 |
| 🛠 أنماط الاستخدام | GUI، CLI، HTTP API |
| 🌍 الترجمة | توطين مجتمعي عبر Weblate |

### مصممة لسير العمل العملي

| سير العمل | القدرة الأساسية |
| --- | --- |
| معالجة لقطات الشاشة | قص واختيار ونسخ النص مباشرة من الالتقاطات المباشرة |
| التعامل الدفعي | معالجة المجلدات، ضبط المعالجة اللاحقة، وتصدير مخرجات نصية منظمة |
| OCR المستندات | قراءة مستندات ممسوحة ضوئيًا وإنتاج ملفات PDF قابلة للبحث |
| عمليات QR | فك تشفير عدد عدة من الرموز وإنشاء عناصر QR/barcode مخصصة |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="معاينة Umi-OCR 1" style="width: 80%;"></p>

![معاينة Umi-OCR 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

<a id="table-of-contents"></a>
## جدول المحتويات

- [✨ الميزات](#features)
- [🧱 هيكل المشروع](#project-structure)
- [🧰 المتطلبات المسبقة](#prerequisites)
- [⚙️ التثبيت](#installation)
- [⬇️ تنزيل الإصدارات](#download-releases)
- [🧪 الاستخدام](#usage)
- [🔧 الإعدادات](#configuration)
- [🧩 أمثلة](#examples)
- [📡 مراجع API](#api-references)
- [🧠 ملاحظات التطوير](#development-notes)
- [🛠️ استكشاف الأخطاء وإصلاحها](#troubleshooting)
- [🌐 التوطين](#localization)
- [🗺️ خارطة الطريق](#roadmap)
- [🤝 المساهمة](#contribution)
- [❤️ Support](#support)
- [📜 الترخيص](#license)

<a id="features"></a>
## الميزات

### OCR لقطات الشاشة

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="Screenshot OCR" style="width: 80%;"></p>

- فعّل OCR عبر اختصار لقطة الشاشة بعد فتح تبويب OCR لقطات الشاشة.
- اللوحة اليسرى تدعم تحديد النص مباشرة داخل معاينة الصورة.
- اللوحة اليمنى تدعم سجل التعرف القابل للتحرير ونسخ سجلات متعددة.
- يدعم الصور الملصقة من الحافظة.
- مرجع التعرف على المعادلات: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### المعالجة اللاحقة للنص (تحليل التخطيط)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Text post-processing" style="width: 80%;"></p>

مخططات مدمجة لإعادة ترتيب كتل OCR وتحسين القراءة:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (مفيد لِمقتطفات الشيفرة)
- `No post-processing` (إخراج OCR خام)

يمكن لهذه المخططات التعامل مع التخطيطات الأفقية والرأسية (يمين إلى يسار) إذا كان نموذج محرك OCR المختار يدعم ذلك.

### OCR دفعي

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="Batch OCR" style="width: 80%;"></p>

- صيغ الإدخال: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- صيغ الإخراج: `txt, jsonl, md, csv(Excel)`
- يدعم قواعد المعالجة اللاحقة للنص من شاشة Screenshot OCR.
- لا يوجد حد عملي لعدد المهام في واجهة UI (يمكن دعم مئات الصور في كل تشغيل).
- يدعم الإغلاق/النوم التلقائي بعد اكتمال المهمة.
- للصور الكبيرة جدًا، اضبط `OCR settings -> image side limit`.

#### مناطق التجاهل

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Ignore region editor" style="width: 80%;"></p>

- استبعاد نصوص العلامات المائية/الشعارات الثابتة أثناء OCR الدفعي.
- ارسم عدة مستطيلات بزر الفأرة الأيمن في محرر Ignore Region.
- ارسم مستطيلات أكبر قليلاً من منطقة العلامة المائية المستهدفة لزيادة المتانة.
- سلوك التجاهل قائم على الكتلة (تُتجاهل الكتل النصية داخل المنطقة).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ignore region scope example" style="width: 80%;"></p>

### OCR المستندات

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="Document OCR" style="width: 80%;"></p>

- صيغ الإدخال: `pdf, xps, epub, mobi, fb2, cbz`
- استخراج النص المضمن عند توفره أو تنفيذ OCR للصفحات الممسوحة.
- تصدير ملفات PDF قابلة للبحث ذات طبقات.
- يدعم مناطق التجاهل (للرؤوس والتذييلات).
- يدعم الإغلاق/النوم التلقائي بعد اكتمال المهمة.

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

وضع القراءة:

- التقط لقطة شاشة أو ألصق أو اسحب صورًا محلية لفك الترميز.
- يدعم عدة أكواد في صورة واحدة.
- يدعم 19 صيغة:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="QR code generate" style="width: 80%;"></p>

وضع الإنشاء:

- أنشئ صور QR/barcode من النص.
- يدعم اختيار الصيغة وإعدادات تصحيح الأخطاء.

### الإعدادات العامة

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Global settings" style="width: 80%;"></p>

- أضف اختصارات واضبط سلوك بدء التشغيل.
- بدّل لغة الواجهة.
- بدّل السمات (إصدار فاتح/داكن).
- اضبط الخط وتكبير الواجهة.
- بدّل إضافات OCR.
- غيّر المظهر (`Interface and Appearance -> Renderer`) عندما يسبب تسريع GPU وميضًا أو إزاحة في الواجهة.

<a id="project-structure"></a>
## هيكل المشروع

### علاقات المستودعات

- [المستودع الرئيسي](https://github.com/hiroi-sora/Umi-OCR)
- [مستودع الإضافات](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [مستودع وقت التشغيل لـ Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [مستودع وقت التشغيل لـ Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### تخطيط وقت التشغيل (التخطيط القياسي للأصل)

`**` يعني أنّ المحتوى المدرج ضمن هذا المستودع الرئيسي.

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

### شجرة المصدر في لقطة المستودع هذه

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

### للمستخدم النهائي

| البند | المتطلب |
| --- | --- |
| نظام التشغيل | Windows 7 x64+ أو Linux x64 |
| المعالج (موصى به) | معالج x64 بدعم AVX (لاستخدام إضافات PaddleOCR) |
| وقت التشغيل (موصى به لويندوز) | Visual C++ runtime للحفاظ على التوافق |

### للمطورين

- اقرأ واتبع إعداد وقت التشغيل حسب المنصة من:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- هذا المستودع لا يوفّر `requirements.txt` أو `pyproject.toml` مستقلة لإعداد pip مباشر.

<a id="installation"></a>
## التثبيت

### الخيار A: حزمة إصدار محمولة (مُوصى بها)

1. نزّل حزمة `.7z` أو حزمة `.7z.exe` القابلة للتنفيذ الذاتي.
2. فك الضغط.
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

لا تُثبّت النسختين معًا (قد يحدث تعارض في الاختصارات). استخدم تبديل الإضافة عند الحاجة.

### الخيار C: البناء/التشغيل عبر مستودعات وقت التشغيل

اتبع تعليمات الإعداد للـ build/runtime من:

- [إعداد وقت التشغيل على Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [إعداد وقت التشغيل على Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="download-releases"></a>
## تنزيل الإصدارات

| المرآة | الرابط | الملاحظات |
| --- | --- | --- |
| Lanzou | [Regional mirror](https://hiroi-sora.lanzoul.com/s/umi-ocr) | مرآة صديقة للصين |
| GitHub | [Latest releases](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | صفحة الإصدارات الأساسية للمشروع الأم |
| SourceForge | [Download mirror](https://sourceforge.net/projects/umi-ocr) | قناة تنزيل بديلة قديمة |

<a id="usage"></a>
## الاستخدام

### البدء السريع

- Umi-OCR محمول؛ لا يحتاج إلى مثبت.
- شغّل `Umi-OCR.exe` بعد فك الضغط.
- إذا فشل بدء التشغيل، راجع قسم [استكشاف الأخطاء وإصلاحها](#troubleshooting).

### لغة الواجهة

في أول تشغيل، يتم اختيار لغة الواجهة تلقائيًا بناءً على لغة النظام.

للتبديل اليدوي: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Language switch" style="width: 80%;"></p>

### علامات التبويب وسير العمل

- افتح علامات التبويب المطلوبة فقط حسب سير عملك.
- فعّل/عطّل دائمًا في الأعلى من الركن العلوي الأيسر لشريط التبويبات.
- ثبّت علامات التبويب من الأعلى يمينًا لتجنب الإغلاق العرضي.

### الاستخدام عبر سطر الأوامر

دليل CLI: [docs/README_CLI.md](docs/README_CLI.md)

التحكم الأساسي:

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

نقاط النهاية الأساسية:

| Endpoint | الغرض |
| --- | --- |
| `/api/ocr/get_options` | خيارات OCR |
| `/api/ocr` | تنفيذ OCR |
| `/api/doc/*` | إعدادات/رفع/نتيجة/تنزيل المستند |
| `/api/qrcode` | فك ترميز QR |
| `/argv` | جسر CLI عبر HTTP |

ملاحظة: في `Global Settings` يجب أن تبقى خدمة HTTP مفعلة (الإعداد الافتراضي). استخدم المضيف المحلي فقط إلا إذا احتجت وصول LAN.

<a id="configuration"></a>
## الإعداد

- تُحفظ إعدادات وقت التشغيل في `UmiOCR-data/.settings` (صيغة INI).
- بعد التعديل اليدوي، طبّق التغييرات عبر:

```bash
umi-ocr --reload
```

- قد تتضمن حالة توافق بدء التشغيل/وقت التشغيل أيضًا:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (لإصدارات بها تسجيل تشغيل)

<a id="examples"></a>
## أمثلة

### المثال 1: OCR دفعي حسب المسار

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### المثال 2: قراءة QR من مسارات متعددة

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### المثال 3: إنشاء QR بحجم صريح

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### المثال 4: استدعاء وحدة متقدمة

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
  - `UmiOCR-data/main.py` (تهيئة وقت التشغيل)
  - `UmiOCR-data/py_src/run.py` (بدء التطبيق)
- بنية الواجهة: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- الخدمات الأساسية:
  - `py_src/server/*` لـ HTTP + نقل الأوامر
  - `py_src/mission/*` لمهام OCR/Doc/QR المكدّسة
  - `py_src/ocr/*` للمعالجة اللاحقة والمخرجات
- محركات OCR المدعومة في النظام:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- إطار وقت التشغيل: [PyStand (customized)](https://github.com/skywind3000/PyStand)

<a id="troubleshooting"></a>
## استكشاف الأخطاء وإصلاحها

للتفاصيل الكاملة: [https://github.com/hiroi-sora/Umi-OCR/issues/447](https://github.com/hiroi-sora/Umi-OCR/issues/447)

فهرس سريع:

| العرض | الانتقال |
| --- | --- |
| لا يمكن العثور على `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| فشل إنشاء سياق OpenGL | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| التطبيق يتوقف عند البدء | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / فشل تهيئة OCR مع مؤشرات MKLDNN/AVX | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| ملف `api-ms-win-crt-runtime-l1-1-0.dll` مفقود | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

<a id="cannot-find-py_main"></a>
### `Cannot find Py_Main()`

- ثبّت VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe
- أو شغّل باستخدام fallback `UmiOCR-data/RUN_GUI.bat`.
- ملاحظة: مشغل `.bat` له قيود (لا يوجد تحكم CLI، وأتمتة اختصار محدودة).

<a id="failed-to-create-opengl-context"></a>
### `Failed to create OpenGL context`

- نزّل تصحيح وقت التشغيل: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- ضع ملف DLL المستخرج في `UmiOCR-data/site-packages/PySide2/`.

<a id="umi-ocrexe-has-stopped-working"></a>
### `Umi-OCR.exe has stopped working`

- يحدث عادةً عند إعادة استخدام الإعدادات عبر إصدارات Windows مختلفة.
- احذف `UmiOCR-data/.pre_settings` ثم أعد المحاولة.

<a id="0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints"></a>
### `0xc0000142` أو فشل تهيئة OCR مع مؤشرات MKLDNN/AVX

- غالبًا المعالج لا يدعم AVX.
- استخدم نسخة RapidOCR أو غيّر عن إضافة PaddleOCR:
  - [إصدارات Umi-OCR_Rapid](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [إضافات Umi-OCR](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### شاشة سوداء مع `OSError` (البرنامج غير موجود)

- شائع في Windows 7 المبكرة غير المحدثة (خاصة إذا كان `KB2533623` مفقودًا).
- الإصلاح الموصى به: شغّل Windows Update بالكامل ثم أعد التشغيل.

### توقف أثناء تصدير PDF قابل للبحث

- غالبًا بسبب نقص تحديثات Windows 7 (خاصة `KB4534310` واعتماداتها).
- الإصلاح الموصى به: ثبّت جميع تحديثات النظام المفقودة عبر Windows Update.

<a id="missing-api-ms-win-crt-runtime-l1-1-0dll"></a>
### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- ثبّت VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe

### وضع الاختصارات يدويًا

إذا فشل إنشاء الاختصار تلقائيًا، ضعها يدويًا:

- قائمة ابدأ: `C:\ProgramData\Microsoft\Windows\Start Menu`
- بدء التشغيل: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

<a id="localization"></a>
## التوطين

هذا المشروع يستخدم Weblate للتوطين التعاوني:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

ملفات README الأخرى في هذا المستودع:

| اللغة | الملف |
| --- | --- |

شكرًا لكل المساهمين في الترجمة:

| المترجم | اللغات المساهم بها |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

إذا وجدت أخطاء أو نواقص، يرجى الرد في [هذا النقاش](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

<a id="roadmap"></a>
## خارطة الطريق

### مكتمل

- بنية صفحة بالتبويبات.
- متحكم OCR API.
- متحكم مهمة OCR.
- مدير السمات بدعم فاتح/داكن.
- OCR دفعي.
- OCR لقطة شاشة.
- آلية مفتاح اختصار.
- قائمة صينية النظام.
- معالجة لاحقة لكتل النص (تحسين التخطيط).
- تنظيف ذاكرة المحرك.
- واجهة متعددة اللغات.
- وضع سطر الأوامر.
- توافق Windows 7.
- صيغة إخراج Excel (CSV).
- مقاطعة لقطة الشاشة باستخدام `Esc`.
- ملفات السمات الخارجية.
- تبديل الخط.
- رسوم تحميل.
- مناطق التجاهل.
- التعرف على QR.
- معاينة الصور أثناء التعرف الدفعي.
- التعرف على PDF.
- فتح الصورة باستخدام عارض الصور المحلي. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- تكرار منطقة لقطة الشاشة السابقة. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- إصلاح مشكلة توافق تعرّف المستندات في Windows 7.
- دعم قراءة/إنشاء QR في واجهات HTTP و CLI. (#423)
- توثيق واجهة QR.
- نقل النظام إلى منصة Linux.
- HTTP document-recognition API.

### خطط طويلة الأجل

النقاط التالية هي أفكار مخطط لها وقد تتطور أثناء التطوير:

- [ ] إعادة هيكلة آلية الإضافة الأساسية.
- [ ] ملحق OCR API على الإنترنت.
- [ ] إضافة مخصّصة للتعرف على المعادلات.
- [ ] تبويب مخصص للمعادلات مع عرض LaTeX.
- [ ] آلية للتحقق من التحديث.
- [ ] وحدات معالجة لاحقة إضافية تتعدى تحليل التخطيط.
- [ ] محفزات أحداث لوظائف الواجهة الرئيسية.
- [ ] OCR دون اتصال معتمد على GPU.
- [ ] ترجمة الصور.
- [ ] ترجمة دون اتصال.
- [ ] OCR بمنطقة ثابتة.
- [ ] التعرف على الجداول إلى إخراج Excel.
- [ ] نظام السجل.
- [ ] توسيع التوافق لمنصات مثل macOS/Ubuntu.

<a id="contribution"></a>
## المساهمة

المساهمات مرحبة.

- أبلغ عن الأخطاء أو قدّم طلبات ميزات عبر [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- ناقش الأفكار في [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- ساهم بالترجمات عبر [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- لأعمال المحرك/الإضافات، انظر أيضًا [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

لإعداد بيئة التطوير، اتبع مستودعات وقت التشغيل حسب المنصة:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

<a id="support"></a>
## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

<a id="license"></a>
## الترخيص

هذا المشروع مرخّص تحت رخصة MIT.

- [LICENSE](LICENSE)


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
