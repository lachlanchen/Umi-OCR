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
  <a href="#telecharger-les-releases">
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
    <a href="#table-des-matieres">Utilisation</a>
    <span> • </span>
    <a href="#telecharger-les-releases">Télécharger les Releases</a>
    <span> • </span>
    <a href="CHANGE_LOG.md">Journal des modifications</a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">Signaler un problème</a>
  </h3>
</div>

<div align="center">
  <strong>Outil OCR gratuit, open source, et traitement par lots hors ligne</strong><br>
  <sub>Compatible avec Windows 7 x64 et Linux x64</sub>
</div>

## 🚀 En un coup d'œil

| Point fort | Détails |
| --- | --- |
| 📦 Distribution | Application de bureau portable (`.7z` et `.7z.exe`) |
| 🧠 Mode de base | OCR par lots hors ligne avec workflows capture, document et QR |
| 🧩 Interfaces | GUI, CLI et API HTTP |
| 🌐 Localisation | Traduction communautaire via Weblate |

---

## Vue d'ensemble

Umi-OCR est un outil OCR orienté bureau, axé sur le traitement hors ligne, les flux par lots haute capacité et les intégrations pragmatiques.

- **Gratuit** : tout le code est open source et libre d'utilisation.
- **Pratique** : extraction et exécution locales, sans dépendance réseau pour l'OCR principal.
- **Efficace** : moteurs OCR intégrés hors ligne avec prise en charge multilingue.
- **Flexible** : prend en charge les workflows GUI, ligne de commande et API HTTP.
- **Riche en fonctionnalités** : OCR de captures d'écran, OCR par lot, OCR de documents, lecture/création de QR codes, point d'entrée pour la reconnaissance de formules.

| ✅ Faits rapides | Détails |
| --- | --- |
| 🧩 Licence | MIT |
| 🌐 Exigence réseau | Aucun réseau requis pour les flux OCR principaux |
| 💻 Plateforme | Windows 7 x64+ / Linux x64 |
| 🛠 Modes d'utilisation | GUI, CLI, API HTTP |
| 🌍 Traduction | Localisation communautaire via Weblate |

### Conçu pour des flux de travail concrets

| Flux | Fonction principale |
| --- | --- |
| Traitement de captures | Recadrez, sélectionnez et transcrivez directement depuis des captures en direct |
| Gestion par lots | Traitez des dossiers, ajustez le post-traitement et exportez des sorties texte structurées |
| OCR documentaire | OCR de documents scannés et création de PDF en couches recherchables |
| Opérations QR | Décodez plusieurs codes et générez vos propres QR/barcodes |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Aperçu Umi-OCR 1" style="width: 80%;"></p>

![Aperçu Umi-OCR 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## Table des matières

- [✨ Fonctionnalités](#fonctionnalites)
- [🧱 Structure du projet](#structure-du-projet)
- [🧰 Prérequis](#prerequis)
- [⚙️ Installation](#installation)
- [⬇️ Télécharger les Releases](#telecharger-les-releases)
- [🧪 Utilisation](#utilisation)
- [🔧 Configuration](#configuration)
- [🧩 Exemples](#exemples)
- [📡 Références API](#references-api)
- [🧠 Notes de développement](#notes-de-developpement)
- [🛠️ Dépannage](#depannage)
- [🌐 Localisation](#localisation)
- [🗺️ Roadmap](#roadmap)
- [🤝 Contribution](#contribution)
- [❤️ Support](#support)
- [📜 Licence](#licence)

## Fonctionnalités

### OCR par capture d'écran

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="OCR par capture d'écran" style="width: 80%;"></p>

- Lancez l'OCR via le raccourci de capture après ouverture de l'onglet Screenshot OCR.
- Le panneau de gauche permet la sélection directe de texte dans l'aperçu d'image.
- Le panneau de droite permet d'éditer l'historique de reconnaissance et de copier plusieurs éléments.
- Prise en charge des images collées depuis le presse-papiers.
- Référence de reconnaissance de formules : [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### Post-traitement de texte (analyse de mise en page)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Post-traitement de texte" style="width: 80%;"></p>

Schémas intégrés pour réordonner les blocs OCR et améliorer la lisibilité :

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (utile pour les extraits de code)
- `No post-processing` (sortie OCR brute)

Ces schémas gèrent les mises en page horizontales et verticales (de droite à gauche) si le modèle OCR sélectionné le supporte.

### OCR par lot

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="OCR par lot" style="width: 80%;"></p>

- Formats d'entrée : `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- Formats de sortie : `txt, jsonl, md, csv(Excel)`
- Prise en charge des règles de post-traitement du texte issues de Screenshot OCR.
- Aucune limite pratique du nombre de tâches dans le flux UI (des centaines d'images par exécution sont prises en charge).
- Prise en charge de l'arrêt automatique / mise en veille après la fin des tâches.
- Pour les images très grandes, ajustez `OCR settings -> image side limit`.

#### Régions ignorées

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Éditeur de régions ignorées" style="width: 80%;"></p>

- Exclut les textes de filigrane/logo stables pendant l'OCR par lot.
- Dessinez plusieurs rectangles avec le clic droit dans l'éditeur de régions ignorées.
- Dessinez des rectangles plus larges que la zone du filigrane cible pour une meilleure robustesse.
- Le comportement d'exclusion est basé sur les blocs (le bloc texte inclus dans la région est ignoré).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Exemple de zone ignorée" style="width: 80%;"></p>

### OCR de documents

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="OCR de documents" style="width: 80%;"></p>

- Formats d'entrée : `pdf, xps, epub, mobi, fb2, cbz`
- Extrait le texte embarqué quand il est disponible ou effectue l'OCR des pages scannées.
- Exporte des PDF en couches recherchables.
- Prise en charge des régions ignorées (pour en-têtes/pieds de page).
- Prise en charge de l'arrêt automatique / mise en veille après fin de tâche.

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

Mode lecture :

- Capturez, collez ou glissez des images locales pour décoder.
- Prise en charge de plusieurs codes dans une même image.
- Prise en charge de 19 formats :

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="Génération QR code" style="width: 80%;"></p>

Mode génération :

- Génère des images QR/barcode à partir de texte.
- Supporte la sélection du format et les paramètres de correction d'erreurs.

### Paramètres globaux

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Paramètres globaux" style="width: 80%;"></p>

- Ajoute des raccourcis et configure le comportement au démarrage.
- Change la langue de l'interface.
- Change les thèmes (variantes clair/sombre).
- Configure la police et l'échelle de l'interface.
- Change les plugins OCR.
- Modifie le moteur de rendu (`Interface and Appearance -> Renderer`) si l'accélération GPU provoque scintillement ou décalage visuel.

## Structure du projet

### Relations entre dépôts

- [Dépôt principal](https://github.com/hiroi-sora/Umi-OCR)
- [Dépôt de plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Dépôt runtime Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Dépôt runtime Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### Mise en page d'exécution (disposition amont canonique)

`**` signifie un contenu inclus dans ce dépôt principal.

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

### Arborescence du dépôt source

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

## Prérequis

### Utilisateurs finaux

| Élément | Exigence |
| --- | --- |
| Système d'exploitation | Windows 7 x64+ ou Linux x64 |
| CPU (recommandé) | CPU x64 avec support AVX (pour les plugins basés sur PaddleOCR) |
| Runtime (Windows recommandé) | Runtime Visual C++ pour la compatibilité |

### Développeurs

- Consultez et suivez la configuration runtime de la plateforme :
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- Ce dépôt ne fournit pas de `requirements.txt` ou `pyproject.toml` pour une configuration directe via pip.

## Installation

### Option A : paquet portable (recommandée)

1. Téléchargez le package `.7z` ou le `.7z.exe` auto-extractible.
2. Extrayez les fichiers.
3. Lancez `Umi-OCR.exe`.

### Option B : Scoop (Windows)

```bash
scoop bucket add extras
```

Variante RapidOCR (meilleure compatibilité) :

```bash
scoop install extras/umi-ocr
```

Variante PaddleOCR (légèrement plus rapide) :

```bash
scoop install extras/umi-ocr-paddle
```

N'installez pas les deux variantes simultanément (des conflits de raccourcis peuvent apparaître). Utilisez le changement de plugin si nécessaire.

### Option C : Build/Run via les dépôts runtime

Suivez les instructions de configuration de build/runtime depuis :

- [Configuration runtime Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Configuration runtime Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Télécharger les Releases

| Miroir | Lien | Remarques |
| --- | --- | --- |
| Lanzou | [Miroir régional](https://hiroi-sora.lanzoul.com/s/umi-ocr) | Miroir convivial pour la Chine |
| GitHub | [Dernières releases](https://github.com/hiroi-sora/Umi-OCR/releases/latest) | Page principale des releases amont |
| SourceForge | [Miroir de téléchargement](https://sourceforge.net/projects/umi-ocr) | Canal alternatif historique |

## Utilisation

### Démarrage rapide

- Umi-OCR est portable ; aucun installateur n'est requis.
- Lancez `Umi-OCR.exe` après extraction.
- Si le démarrage échoue, consultez [Dépannage](#depannage).

### Langue de l'interface

Au premier lancement, la langue de l'UI est automatiquement choisie selon la locale du système.

Pour la basculer manuellement : `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Changement de langue" style="width: 80%;"></p>

### Onglets et flux de travail

- Ouvrez uniquement les onglets nécessaires à votre flux.
- Activez l'affichage toujours au-dessus depuis le coin supérieur gauche de la barre d'onglets.
- Verrouillez les onglets depuis le coin supérieur droit pour éviter les fermetures accidentelles.

### Utilisation en ligne de commande

Manuel CLI : [docs/README_CLI.md](docs/README_CLI.md)

Contrôles de base :

```bash
umi-ocr --help
umi-ocr --show
umi-ocr --hide
umi-ocr --quit
umi-ocr --reload
```

Commandes OCR :

```bash
umi-ocr --screenshot
umi-ocr --clipboard
umi-ocr --path "D:/img1.png" "D:/img2.png" "D:/image/test"
```

Capture d'écran à région fixe :

```bash
umi-ocr --screenshot screen=1 rect=50,100,300,200
```

Commandes QR :

```bash
umi-ocr --qrcode_read "D:/qr.png"
umi-ocr --qrcode_create "hello world" "D:/out.jpeg" 256 256
```

Options de sortie :

```bash
umi-ocr --screenshot --clip
umi-ocr --screenshot --output result.txt
umi-ocr --screenshot "-->" result.txt
umi-ocr --screenshot --output_append result.txt
umi-ocr "-->>" result.txt
```

### Utilisation via API HTTP

Documentation HTTP : [docs/http/README.md](docs/http/README.md)

Points d'entrée clés :

| Endpoint | Objectif |
| --- | --- |
| `/api/ocr/get_options` | Options OCR |
| `/api/ocr` | Exécuter l'OCR |
| `/api/doc/*` | Options/Envoi/Résultat/Téléchargement de documents |
| `/api/qrcode` | Décodage QR |
| `/argv` | Pont CLI via HTTP |

Remarque : dans `Global Settings`, le service HTTP doit rester activé (par défaut). Utilisez un hôte local sauf si l'accès LAN est requis.

## Configuration

- Les paramètres runtime sont stockés dans `UmiOCR-data/.settings` (format INI).
- Après modification manuelle de la configuration, appliquez les changements avec :

```bash
umi-ocr --reload
```

- Certains états de compatibilité au démarrage/runtime peuvent aussi impliquer :
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (pour les versions avec journalisation runtime)

## Exemples

### Exemple 1 : OCR par lot par chemin

```bash
umi-ocr --path "D:/book_pages" --output "D:/ocr_output.txt"
```

### Exemple 2 : Lire des QR depuis plusieurs chemins

```bash
umi-ocr --qrcode_read "D:/qr/1.png" "D:/qr/2.png"
```

### Exemple 3 : Générer un QR avec taille explicite

```bash
umi-ocr --qrcode_create "https://github.com/hiroi-sora/Umi-OCR" "D:/qr_out.jpeg" 128 256
```

### Exemple 4 : Appel de module avancé

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## Références API

- Manuel de ligne de commande : [docs/README_CLI.md](docs/README_CLI.md)
- Manuel HTTP API : [docs/http/README.md](docs/http/README.md)
- API OCR : [docs/http/api_ocr.md](docs/http/api_ocr.md)
- API document : [docs/http/api_doc.md](docs/http/api_doc.md)
- API QR : [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- Pont argv HTTP : [docs/http/argv.md](docs/http/argv.md)

## Notes de développement

- Points d'entrée :
  - `UmiOCR-data/main.py` (démarrage runtime)
  - `UmiOCR-data/py_src/run.py` (lancement de l'application)
- Stack UI : PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- Services principaux :
  - `py_src/server/*` pour HTTP + transport de commandes
  - `py_src/mission/*` pour tâches OCR/documents/QR en file
  - `py_src/ocr/*` pour le post-traitement OCR et les sorties
- Moteurs OCR pris en charge par l'écosystème :
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- Framework runtime : [PyStand (personnalisé)](https://github.com/skywind3000/PyStand)

## Dépannage

Pour les détails complets de dépannage : [https://github.com/hiroi-sora/Umi-OCR/issues/447](https://github.com/hiroi-sora/Umi-OCR/issues/447)

Index rapide :

| Symptôme | Aller à |
| --- | --- |
| Cannot find `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| Échec de création du contexte OpenGL | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| Crash au démarrage de l'app | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / échec d'init OCR avec indices MKLDNN/AVX | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| `api-ms-win-crt-runtime-l1-1-0.dll` manquant | [`Missing api-ms-win-crt-runtime-l1-1-0.dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- Installez le runtime VC : https://aka.ms/vs/17/release/vc_redist.x64.exe
- Ou lancez avec le fallback `UmiOCR-data/RUN_GUI.bat`.
- Remarque : le lanceur `.bat` a des limites (pas de contrôle CLI, automatisation des raccourcis limitée).

### `Failed to create OpenGL context`

- Téléchargez le correctif runtime : https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- Placez la DLL extraite dans `UmiOCR-data/site-packages/PySide2/`.

### `Umi-OCR.exe has stopped working`

- Phénomène fréquent après réutilisation d'une configuration entre versions Windows différentes.
- Supprimez `UmiOCR-data/.pre_settings` puis réessayez.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- Le CPU ne prend probablement pas en charge AVX.
- Utilisez la variante RapidOCR ou changez de plugin PaddleOCR :
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Black console with `OSError` (program not found)

- Fréquent sur les premières versions de Windows 7 non patchées (surtout `KB2533623` manquant).
- Correction recommandée : exécutez toutes les mises à jour Windows puis redémarrez.

### Crash while exporting searchable PDF

- Souvent causé par des mises à jour Windows 7 manquantes (notamment `KB4534310` et dépendances).
- Remède recommandé : installez toutes les mises à jour système manquantes via Windows Update.

### Missing `api-ms-win-crt-runtime-l1-1-0.dll`

- Installez le runtime VC : https://aka.ms/vs/17/release/vc_redist.x64.exe

### Manual Shortcut Placement

- Si la création automatique de raccourcis échoue, placez-les manuellement :

- Menu Démarrer : `C:\ProgramData\Microsoft\Windows\Start Menu`
- Démarrage : `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## Localisation

Ce projet utilise Weblate pour la localisation collaborative :

- [Weblate : Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

Fichiers README dans ce dépôt :

| Langue | Fichier |
| --- | --- |

Remerciements aux traducteurs :

| Traducteur | Langues contributrices |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

En cas d'erreur ou d'omission, merci de répondre dans [cette discussion](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

## Roadmap

### Réalisé

- Architecture à onglets.
- Contrôleur d'API OCR.
- Contrôleur de mission/tâches OCR.
- Gestionnaire de thèmes avec support clair/sombre.
- OCR par lot.
- OCR par capture d'écran.
- Mécanisme de raccourci.
- Menu de la zone de notification.
- Post-traitement des blocs de texte (optimisation de la mise en page).
- Nettoyage mémoire du moteur.
- Interface multilingue.
- Mode ligne de commande.
- Compatibilité Windows 7.
- Format de sortie Excel (CSV).
- Interruption de capture par `Esc`.
- Fichiers de thème externes.
- Changement de police.
- Animation de chargement.
- Régions ignorées.
- Reconnaissance de QR code.
- Prévisualisation d'image dans la reconnaissance par lot.
- Reconnaissance PDF.
- Ouverture d'image avec le visualiseur local. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- Répétition de la région de capture précédente. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- Correction de la compatibilité Windows 7 dans la reconnaissance de documents.
- Support de lecture/création QR dans HTTP et CLI. (#423)
- Documentation d'interface QR.
- Migration de la plateforme Linux.
- API de reconnaissance documentaire HTTP.

### Plans à long terme

Les éléments suivants sont des idées prévues et peuvent évoluer durant le développement :

- [ ] Refactoriser le mécanisme de plugin sous-jacent.
- [ ] Plugin OCR avec API en ligne.
- [ ] Plugin de reconnaissance de formule indépendant.
- [ ] Onglet dédié aux formules avec rendu LaTeX.
- [ ] Mécanisme de vérification des mises à jour.
- [ ] Modules de post-traitement supplémentaires au-delà du parseur de mise en page.
- [ ] Déclencheurs d'événements pour les fonctions clés de l'interface.
- [ ] OCR hors ligne basé sur GPU.
- [ ] Traduction d'image.
- [ ] Traduction hors ligne.
- [ ] OCR région fixe.
- [ ] Reconnaissance de tableaux vers sortie Excel.
- [ ] Système d'historique.
- [ ] Extension de compatibilité pour plateformes comme macOS/Ubuntu.

## Contribution

Les contributions sont bienvenues.

- Signalez des bugs ou demandez des fonctionnalités via [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- Discutez d'idées dans [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- Contribuez à la traduction via [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- Pour le travail sur les moteurs/plugins, consultez aussi [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

Pour la configuration de développement, suivez les dépôts runtime de la plateforme :

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

## License

Ce projet est sous licence MIT.

- [LICENSE](LICENSE)
