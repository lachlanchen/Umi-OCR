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
  <a href="#descargar-versiones">
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
    <a href="#table-of-contents">Uso</a>
    <span> • </span>
    <a href="#descargar-versiones">Descargar versiones</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">Registro de cambios</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">Reportar problemas</a>
  </h3>
</div>

<div align="center">
  <strong>Software OCR por lotes, libre, de código abierto y sin conexión</strong><br>
  <sub>Compatible con Windows 7 x64 y Linux x64</sub>
</div>

## Resumen

Umi-OCR es una herramienta OCR orientada al escritorio, centrada en el procesamiento sin conexión, flujos por lotes de alto rendimiento e integraciones prácticas.

- **Gratis**: Todo el código es de código abierto y de uso gratuito.
- **Cómodo**: Extrae y ejecuta localmente, sin dependencia de red para el OCR principal.
- **Eficiente**: Incluye motores OCR sin conexión con soporte multilingüe.
- **Flexible**: Admite flujos GUI, control por línea de comandos y APIs HTTP.
- **Completo**: OCR de captura, OCR por lotes, OCR de documentos, lectura/creación de códigos QR y punto de entrada para reconocimiento de fórmulas.

| ✅ Datos rápidos | Detalles |
| --- | --- |
| 🧩 Licencia | MIT |
| 🌐 Requisito de red | No se necesita red para los flujos OCR principales |
| 💻 Plataforma | Windows 7 x64+ / Linux x64 |
| 🛠 Modos de uso | GUI, CLI, API HTTP |
| 🌍 Traducción | Localización comunitaria basada en Weblate |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Vista previa 1 de Umi-OCR" style="width: 80%;"></p>

![Vista previa 2 de Umi-OCR](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## Tabla de contenidos

- [Funciones](#funciones)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Requisitos previos](#requisitos-previos)
- [Instalación](#instalación)
- [Descargar versiones](#descargar-versiones)
- [Uso](#uso)
- [Configuración](#configuración)
- [Ejemplos](#ejemplos)
- [Referencias de API](#referencias-de-api)
- [Notas de desarrollo](#notas-de-desarrollo)
- [Solución de problemas](#solución-de-problemas)
- [Localización](#localización)
- [Hoja de ruta](#hoja-de-ruta)
- [Contribución](#contribución)
- [Soporte](#soporte)
- [Licencia](#licencia)

## Funciones

### OCR de captura de pantalla

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="OCR de captura de pantalla" style="width: 80%;"></p>

- Activa OCR con el atajo de captura tras abrir la pestaña de OCR de captura.
- El panel izquierdo permite seleccionar texto directamente en la vista previa de la imagen.
- El panel derecho permite editar el historial de reconocimiento y copiar múltiples registros.
- Admite imágenes pegadas desde el portapapeles.
- Referencia de reconocimiento de fórmulas: [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### Posprocesamiento de texto (análisis de diseño)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Posprocesamiento de texto" style="width: 80%;"></p>

Esquemas integrados para reordenar bloques OCR y mejorar la legibilidad:

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (útil para fragmentos de código)
- `No post-processing` (salida OCR sin procesar)

Estos esquemas pueden manejar diseño horizontal y vertical (de derecha a izquierda) si el modelo del motor OCR seleccionado lo admite.

### OCR por lotes

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="OCR por lotes" style="width: 80%;"></p>

- Formatos de entrada: `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- Formatos de salida: `txt, jsonl, md, csv(Excel)`
- Admite reglas de posprocesamiento de texto de OCR de captura.
- Sin límite práctico de número de tareas en el flujo UI (se admiten cientos de imágenes por ejecución).
- Admite apagado/suspensión automáticos tras completar tareas.
- Para imágenes muy grandes, ajusta `OCR settings -> image side limit`.

#### Ignorar regiones

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Editor de región ignorada" style="width: 80%;"></p>

- Excluye texto estable de marca de agua/logo durante OCR por lotes.
- Dibuja múltiples rectángulos con el botón derecho en el editor Ignore Region.
- Dibuja rectángulos más grandes que el área objetivo de la marca de agua para mayor robustez.
- El comportamiento de ignorado es por bloques (el bloque de texto dentro de la región se ignora).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Ejemplo de alcance de región ignorada" style="width: 80%;"></p>

### OCR de documentos

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="OCR de documentos" style="width: 80%;"></p>

- Formatos de entrada: `pdf, xps, epub, mobi, fb2, cbz`
- Extrae texto incrustado cuando está disponible u OCR en páginas escaneadas.
- Exporta PDF en capas y con búsqueda.
- Admite regiones ignoradas (para encabezados/pies).
- Admite apagado/suspensión automáticos tras completar tareas.

### Código QR

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="Código QR" style="width: 80%;"></p>

Modo de lectura:

- Captura, pega o arrastra imágenes locales para decodificar.
- Admite múltiples códigos en una sola imagen.
- Admite 19 formatos:

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="Generación de código QR" style="width: 80%;"></p>

Modo de generación:

- Genera imágenes QR/código de barras a partir de texto.
- Admite selección de formato y ajustes de corrección de errores.

### Configuración global

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Configuración global" style="width: 80%;"></p>

- Añade atajos y configura el comportamiento de inicio.
- Cambia el idioma de la interfaz.
- Cambia temas (variantes claro/oscuro).
- Configura fuente y escalado de interfaz.
- Cambia plugins OCR.
- Cambia el renderizador (`Interface and Appearance -> Renderer`) cuando la aceleración GPU cause parpadeo o desplazamiento de la UI.

## Estructura del proyecto

### Relaciones entre repositorios

- [Repositorio principal](https://github.com/hiroi-sora/Umi-OCR)
- [Repositorio de plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Repositorio de runtime para Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Repositorio de runtime para Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### Diseño del runtime (diseño canónico upstream)

`**` significa contenido incluido en este repositorio principal.

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

### Árbol de código en esta instantánea del repositorio

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

## Requisitos previos

### Usuarios finales

| Item | Requisito |
| --- | --- |
| Sistema operativo | Windows 7 x64+ o Linux x64 |
| CPU (recomendado) | CPU x64 con soporte AVX (para plugins basados en PaddleOCR) |
| Runtime (Windows recomendado) | Runtime de Visual C++ para compatibilidad |

### Desarrolladores

- Lee y sigue la configuración de runtime por plataforma en:
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- Este repositorio no proporciona un `requirements.txt` ni `pyproject.toml` independiente para instalación directa con pip.

## Instalación

### Opción A: Paquete portable de lanzamiento (recomendado)

1. Descarga el paquete `.7z` o autoextraíble `.7z.exe`.
2. Extrae los archivos.
3. Ejecuta `Umi-OCR.exe`.

### Opción B: Scoop (Windows)

```bash
scoop bucket add extras
```

Variante RapidOCR (mejor compatibilidad):

```bash
scoop install extras/umi-ocr
```

Variante PaddleOCR (ligeramente más rápida):

```bash
scoop install extras/umi-ocr-paddle
```

No instales ambas variantes a la vez (pueden ocurrir conflictos de accesos directos). Usa el cambio de plugin si lo necesitas.

### Opción C: Compilar/Ejecutar mediante repositorios runtime

Sigue las instrucciones de arranque de compilación/runtime de:

- [Configuración runtime Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Configuración runtime Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Descargar versiones

| Mirror | Enlace | Notas |
| --- | --- | --- |
| Lanzou | https://hiroi-sora.lanzoul.com/s/umi-ocr | Mirror regional |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | Página principal de versiones upstream |
| SourceForge | https://sourceforge.net/projects/umi-ocr | Mirror alternativo de descarga |

## Uso

### Primeros pasos

- Umi-OCR es portable; no requiere instalador.
- Ejecuta `Umi-OCR.exe` tras extraer.
- Si falla al iniciar, consulta [Solución de problemas](#solución-de-problemas).

### Idioma de la interfaz

En el primer inicio, el idioma de la UI se selecciona automáticamente según la configuración regional del sistema.

Para cambiarlo manualmente: `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Cambio de idioma" style="width: 80%;"></p>

### Pestañas y flujo de trabajo

- Abre solo las pestañas necesarias para tu flujo.
- Activa/desactiva siempre visible desde la esquina superior izquierda de la barra de pestañas.
- Bloquea pestañas desde la parte superior derecha para evitar cierres accidentales.

### Uso por línea de comandos

Manual de CLI: [docs/README_CLI.md](docs/README_CLI.md)

Controles básicos:

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

Comandos OCR:

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

Captura con región fija:

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

Comandos QR:

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

Opciones de salida:

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr --screenshot "-->>" result.txt
```

### Uso de API HTTP

Documentación HTTP: [docs/http/README.md](docs/http/README.md)

Endpoints clave:

| Endpoint | Propósito |
| --- | --- |
| `/api/ocr/get_options` | Opciones OCR |
| `/api/ocr` | Ejecutar OCR |
| `/api/doc/*` | Opciones/carga/resultado/descarga de documentos |
| `/api/qrcode` | Decodificación QR |
| `/argv` | Puente de CLI sobre HTTP |

Nota: En `Global Settings`, el servicio HTTP debe mantenerse habilitado (valor predeterminado). Usa host solo local salvo que requieras acceso LAN.

## Configuración

- Los ajustes de runtime se guardan en `UmiOCR-data/.settings` (formato INI).
- Tras editar la configuración manualmente, aplica los cambios con:

```bash
umi-ocr --reload
```

- Parte del estado de compatibilidad de inicio/runtime también puede involucrar:
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (para versiones con logging de runtime)

## Ejemplos

### Ejemplo 1: OCR por lotes por ruta

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### Ejemplo 2: Leer QR desde múltiples rutas

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### Ejemplo 3: Generar QR con tamaño explícito

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### Ejemplo 4: Invocación avanzada de módulos

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## Referencias de API

- Manual de línea de comandos: [docs/README_CLI.md](docs/README_CLI.md)
- Manual de API HTTP: [docs/http/README.md](docs/http/README.md)
- API OCR: [docs/http/api_ocr.md](docs/http/api_ocr.md)
- API de documentos: [docs/http/api_doc.md](docs/http/api_doc.md)
- API QR: [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- Puente argv HTTP: [docs/http/argv.md](docs/http/argv.md)

## Notas de desarrollo

- Puntos de entrada:
  - `UmiOCR-data/main.py` (bootstrap de runtime)
  - `UmiOCR-data/py_src/run.py` (inicio de aplicación)
- Stack UI: PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- Servicios principales:
  - `py_src/server/*` para transporte HTTP + comandos
  - `py_src/mission/*` para tareas OCR/Doc/QR en cola
  - `py_src/ocr/*` para posprocesamiento OCR y salidas
- Motores OCR compatibles en el ecosistema:
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- Framework runtime: [PyStand (customized)](https://github.com/skywind3000/PyStand)

## Solución de problemas

Para todos los detalles de solución de problemas: https://github.com/hiroi-sora/Umi-OCR/issues/447

Índice rápido:

| Síntoma | Ir a |
| --- | --- |
| Cannot find `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| OpenGL context creation failed | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| App crashes on start | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / fallo de inicialización OCR | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| Falta `api-ms-win-crt-runtime-l1-1-0.dll` | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- Instala VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe
- O ejecuta con el fallback `UmiOCR-data/RUN_GUI.bat`.
- Nota: El lanzador `.bat` tiene limitaciones (sin control CLI y con automatización de atajos limitada).

### `Failed to create OpenGL context`

- Descarga el parche runtime: https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- Coloca el DLL extraído en `UmiOCR-data/site-packages/PySide2/`.

### `Umi-OCR.exe has stopped working`

- Común tras reutilizar configuración entre distintas versiones de Windows.
- Elimina `UmiOCR-data/.pre_settings` y vuelve a intentar.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- Es probable que la CPU no tenga AVX.
- Usa la variante RapidOCR o cambia a un plugin distinto de PaddleOCR:
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Consola negra con `OSError` (program not found)

- Común en Windows 7 inicial sin parches (especialmente si falta `KB2533623`).
- Solución recomendada: ejecutar Windows Update completo y reiniciar.

### Bloqueo al exportar PDF con búsqueda

- Suele deberse a actualizaciones faltantes de Windows 7 (especialmente `KB4534310` y dependencias).
- Solución recomendada: instalar todas las actualizaciones pendientes mediante Windows Update.

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- Instala VC runtime: https://aka.ms/vs/17/release/vc_redist.x64.exe

### Colocación manual de accesos directos

Si falla la creación automática de accesos directos, colócalos manualmente:

- Menú Inicio: `C:\ProgramData\Microsoft\Windows\Start Menu`
- Inicio automático: `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## Localización

Este proyecto usa Weblate para localización colaborativa:

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

Archivos de idioma del README en este repositorio:

| Idioma | Archivo |
| --- | --- |

Gracias a todos los traductores:

| Traductor | Idiomas aportados |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

Si hay errores u omisiones, responde en [esta discusión](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

## Hoja de ruta

### Completado

- Arquitectura por páginas de pestañas.
- Controlador OCR API.
- Controlador de tareas/misiones OCR.
- Gestor de temas con soporte claro/oscuro.
- OCR por lotes.
- OCR de captura de pantalla.
- Mecanismo de atajos.
- Menú de bandeja del sistema.
- Posprocesamiento de bloques de texto (optimización de diseño).
- Limpieza de memoria del motor.
- UI multilenguaje.
- Modo de línea de comandos.
- Compatibilidad con Windows 7.
- Formato de salida Excel (CSV).
- Interrupción con `Esc` para captura.
- Archivos de tema externos.
- Cambio de fuente.
- Animación de carga.
- Regiones ignoradas.
- Reconocimiento de código QR.
- Vista previa de imagen en reconocimiento por lotes.
- Reconocimiento PDF.
- Abrir imagen con visor local de imágenes. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- Repetir región de captura anterior. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- Corregido problema de compatibilidad de reconocimiento de documentos en Windows 7.
- Soporte de lectura/creación de QR en interfaces HTTP y CLI. (#423)
- Documentación de interfaz QR.
- Migración a plataforma Linux.
- API HTTP de reconocimiento de documentos.

### Planes a largo plazo

Los siguientes elementos son ideas planificadas y pueden evolucionar durante el desarrollo:

- [ ] Refactorizar el mecanismo interno de plugins.
- [ ] Plugin de API OCR en línea.
- [ ] Plugin independiente de reconocimiento de fórmulas.
- [ ] Pestaña dedicada a fórmulas con renderizado LaTeX.
- [ ] Mecanismo de comprobación de actualizaciones.
- [ ] Módulos adicionales de posprocesamiento más allá del análisis de diseño.
- [ ] Disparadores de eventos para funciones clave de la interfaz.
- [ ] OCR sin conexión basado en GPU.
- [ ] Traducción de imágenes.
- [ ] Traducción sin conexión.
- [ ] OCR de región fija.
- [ ] Reconocimiento de tablas con salida a Excel.
- [ ] Sistema de historial.
- [ ] Ampliación de compatibilidad para plataformas como macOS/Ubuntu.

## Contribución

Las contribuciones son bienvenidas.

- Reporta errores o solicita funciones mediante [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- Debate ideas en [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- Contribuye traducciones mediante [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- Para trabajo de motor/plugin, consulta también [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

Para configurar el entorno de desarrollo, sigue los repositorios runtime por plataforma:

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Soporte

Umi-OCR se desarrolla y mantiene principalmente en el tiempo libre de [hiroi-sora](https://github.com/hiroi-sora).

Si este proyecto te ayuda, se agradece el patrocinio:

- Afdian (CN): https://afdian.com/a/hiroi-sora

## Historial de estrellas

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.

- [LICENSE](LICENSE)
