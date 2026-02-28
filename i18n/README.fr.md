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
  <a href="#telecharger-les-releases">
    <img src="https://img.shields.io/github/downloads/hiroi-sora/Umi-OCR/total?style=flat-square" alt="téléchargements">
  </a>
  <a href="https://star-history.com/#hiroi-sora/Umi-OCR">
    <img src="https://img.shields.io/github/stars/hiroi-sora/Umi-OCR?style=flat-square" alt="étoiles">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/forks">
    <img src="https://img.shields.io/github/forks/hiroi-sora/Umi-OCR?style=flat-square" alt="forks">
  </a>
  <a href="https://hosted.weblate.org/engage/umi-ocr/">
    <img src="https://hosted.weblate.org/widget/umi-ocr/svg-badge.svg" alt="statut de traduction">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%207%2B%20%7C%20Linux%20x64-2ea44f?style=flat-square" alt="plateforme">
  <img src="https://img.shields.io/badge/OCR-Offline-1f6feb?style=flat-square" alt="OCR hors ligne">
  <img src="https://img.shields.io/badge/Interface-GUI%20%7C%20CLI%20%7C%20HTTP-f97316?style=flat-square" alt="interfaces">
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
  <strong>Logiciel OCR batch hors ligne, gratuit et open source</strong><br>
  <sub>Compatible avec Windows 7 x64 et Linux x64</sub>
</div>

## Vue d'ensemble

Umi-OCR est un outil OCR orienté poste de travail, conçu pour le traitement hors ligne, les workflows batch à haut débit et les intégrations pratiques.

- **Gratuit** : tout le code est open source et libre d'utilisation.
- **Pratique** : extraction et exécution en local, sans dépendance réseau pour l'OCR principal.
- **Efficace** : moteurs OCR hors ligne intégrés avec prise en charge multilingue.
- **Flexible** : prend en charge les workflows GUI, le contrôle en ligne de commande et les API HTTP.
- **Complet** : OCR par capture d'écran, OCR batch, OCR de documents, lecture/création de QR code, point d'entrée de reconnaissance de formules.

| ✅ Infos rapides | Détails |
| --- | --- |
| 🧩 Licence | MIT |
| 🌐 Besoin réseau | Aucun réseau nécessaire pour les workflows OCR principaux |
| 💻 Plateforme | Windows 7 x64+ / Linux x64 |
| 🛠 Modes d'utilisation | GUI, CLI, API HTTP |
| 🌍 Traduction | Localisation communautaire basée sur Weblate |

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="Aperçu Umi-OCR 1" style="width: 80%;"></p>

![Aperçu Umi-OCR 2](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## Table des matières

- [Fonctionnalités](#fonctionnalites)
- [Structure du projet](#structure-du-projet)
- [Prérequis](#prerequis)
- [Installation](#installation)
- [Télécharger les Releases](#telecharger-les-releases)
- [Utilisation](#utilisation)
- [Configuration](#configuration)
- [Exemples](#exemples)
- [Références API](#references-api)
- [Notes de développement](#notes-de-developpement)
- [Dépannage](#depannage)
- [Localisation](#localisation)
- [Roadmap](#roadmap)
- [Contribution](#contribution)
- [Support](#support)
- [Licence](#licence)

## Fonctionnalités

### OCR par capture d'écran

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097aba8e.png" alt="OCR par capture d'écran" style="width: 80%;"></p>

- Déclenchez l'OCR via le raccourci de capture après avoir ouvert l'onglet Screenshot OCR.
- Le panneau de gauche permet la sélection directe de texte dans l'aperçu d'image.
- Le panneau de droite propose un historique de reconnaissance modifiable et la copie multi-enregistrements.
- Prend en charge les images collées depuis le presse-papiers.
- Référence reconnaissance de formules : [Issue #254](https://github.com/hiroi-sora/Umi-OCR/issues/254)

#### Post-traitement du texte (analyse de mise en page)

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559909f3e378.png" alt="Post-traitement du texte" style="width: 80%;"></p>

Schémas intégrés pour réordonner les blocs OCR et améliorer la lisibilité :

- `Multi-column - natural paragraphs`
- `Multi-column - always line break`
- `Multi-column - no line break`
- `Single-column - natural paragraphs`
- `Single-column - always line break`
- `Single-column - no line break`
- `Single-column - preserve indentation` (utile pour les extraits de code)
- `No post-processing` (sortie OCR brute)

Ces schémas peuvent gérer les mises en page horizontales et verticales (de droite à gauche) si le modèle du moteur OCR sélectionné le permet.

### OCR batch

<p align="center"><img src="https://tupian.li/images/2023/11/19/655990a2511e0.png" alt="OCR batch" style="width: 80%;"></p>

- Formats d'entrée : `jpg, jpe, jpeg, jfif, png, webp, bmp, tif, tiff`
- Formats de sortie : `txt, jsonl, md, csv(Excel)`
- Prend en charge les règles de post-traitement du texte de Screenshot OCR.
- Pas de limite pratique du nombre de tâches dans le workflow UI (des centaines d'images par exécution sont prises en charge).
- Prend en charge l'arrêt/la mise en veille automatiques une fois la tâche terminée.
- Pour les images très volumineuses, ajustez `OCR settings -> image side limit`.

#### Régions à ignorer

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911d28be7.png" alt="Éditeur des régions à ignorer" style="width: 80%;"></p>

- Exclut les textes de watermark/logo stables pendant l'OCR batch.
- Dessinez plusieurs rectangles avec le bouton droit de la souris dans l'éditeur Ignore Region.
- Dessinez des rectangles plus grands que la zone de watermark cible pour une meilleure robustesse.
- Le comportement d'ignorance est basé sur les blocs (un bloc de texte dans la région est ignoré).

<p align="center"><img src="https://tupian.li/images/2024/05/30/66587bf03ae15.png" alt="Exemple de portée des régions à ignorer" style="width: 80%;"></p>

### OCR de documents

<p align="center"><img src="https://github.com/hiroi-sora/Umi-OCR/assets/56373419/fc2266ee-b9b7-4079-8b10-6610e6da6cf5" alt="OCR de documents" style="width: 80%;"></p>

- Formats d'entrée : `pdf, xps, epub, mobi, fb2, cbz`
- Extrait le texte intégré quand il est disponible ou effectue l'OCR des pages scannées.
- Exporte des PDF superposés et recherchables.
- Prend en charge les régions à ignorer (pour en-têtes/pieds de page).
- Prend en charge l'arrêt/la mise en veille automatiques une fois la tâche terminée.

### QR Code

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991268d6b1.png" alt="QR code" style="width: 80%;"></p>

Mode lecture :

- Capturez, collez ou glissez des images locales pour le décodage.
- Prend en charge plusieurs codes dans une même image.
- Prend en charge 19 formats :

`Aztec`,`Codabar`,`Code128`,`Code39`,`Code93`,`DataBar`,`DataBarExpanded`,`DataMatrix`,`EAN13`,`EAN8`,`ITF`,`LinearCodes`,`MatrixCodes`,`MaxiCode`,`MicroQRCode`,`PDF417`,`QRCode`,`UPCA`,`UPCE`

<p align="center"><img src="https://tupian.li/images/2023/11/19/6559911cda737.png" alt="Génération de QR code" style="width: 80%;"></p>

Mode génération :

- Génère des images QR/code-barres à partir de texte.
- Prend en charge le choix du format et les paramètres de correction d'erreur.

### Paramètres globaux

<p align="center"><img src="https://tupian.li/images/2023/11/19/655991252e780.png" alt="Paramètres globaux" style="width: 80%;"></p>

- Ajoutez des raccourcis et configurez le comportement au démarrage.
- Changez la langue de l'interface.
- Changez de thème (variantes clair/sombre).
- Configurez la police et l'échelle de l'interface.
- Changez de plugin OCR.
- Modifiez le moteur de rendu (`Interface and Appearance -> Renderer`) si l'accélération GPU provoque des scintillements ou un décalage UI.

## Structure du projet

### Relations entre dépôts

- [Dépôt principal](https://github.com/hiroi-sora/Umi-OCR)
- [Dépôt des plugins](https://github.com/hiroi-sora/Umi-OCR_plugins)
- [Dépôt runtime Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Dépôt runtime Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

### Structure runtime (structure canonique amont)

`**` indique le contenu inclus dans ce dépôt principal.

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

### Arborescence source dans cet instantané du dépôt

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
| CPU (recommandé) | CPU x64 avec prise en charge AVX (pour les plugins basés sur PaddleOCR) |
| Runtime (Windows recommandé) | Runtime Visual C++ pour la compatibilité |

### Développeurs

- Lisez et suivez la configuration runtime de la plateforme :
  - [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
  - [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)
- Ce dépôt ne fournit pas de `requirements.txt` ou de `pyproject.toml` autonome pour une installation directe via pip.

## Installation

### Option A : Package release portable (recommandé)

1. Téléchargez le package `.7z` ou auto-extractible `.7z.exe`.
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

N'installez pas les deux variantes simultanément (conflits de raccourcis possibles). Utilisez le changement de plugin si nécessaire.

### Option C : Build/Run via les dépôts runtime

Suivez les instructions de bootstrap build/runtime :

- [Configuration runtime Windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Configuration runtime Linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Télécharger les Releases

| Miroir | Lien | Notes |
| --- | --- | --- |
| Lanzou | https://hiroi-sora.lanzoul.com/s/umi-ocr | Miroir régional |
| GitHub | https://github.com/hiroi-sora/Umi-OCR/releases/latest | Page de release amont principale |
| SourceForge | https://sourceforge.net/projects/umi-ocr | Miroir de téléchargement alternatif |

## Utilisation

### Démarrage rapide

- Umi-OCR est portable ; aucun installateur n'est requis.
- Lancez `Umi-OCR.exe` après extraction.
- Si le démarrage échoue, voir [Dépannage](#depannage).

### Langue de l'interface

Au premier lancement, la langue de l'UI est sélectionnée automatiquement selon la locale système.

Pour changer manuellement : `Global Settings -> Language`.

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599c3f9e600.png" alt="Changement de langue" style="width: 80%;"></p>

### Onglets et workflow

- Ouvrez uniquement les onglets nécessaires à votre workflow.
- Activez/désactivez le mode toujours au premier plan depuis le coin supérieur gauche de la barre d'onglets.
- Verrouillez les onglets depuis le coin supérieur droit pour éviter une fermeture accidentelle.

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

Capture d'écran avec région fixe :

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
umi-ocr --screenshot "-->>" result.txt
```

### Utilisation de l'API HTTP

Documentation HTTP : [docs/http/README.md](docs/http/README.md)

Endpoints principaux :

| Endpoint | Rôle |
| --- | --- |
| `/api/ocr/get_options` | Options OCR |
| `/api/ocr` | Exécuter l'OCR |
| `/api/doc/*` | Options/upload/résultat/téléchargement document |
| `/api/qrcode` | Décodage QR |
| `/argv` | Bridge CLI via HTTP |

Note : dans `Global Settings`, le service HTTP doit rester activé (par défaut). Utilisez un hôte local uniquement, sauf si un accès LAN est requis.

## Configuration

- Les paramètres runtime sont stockés dans `UmiOCR-data/.settings` (format INI).
- Après modification manuelle de la config, appliquez les changements avec :

```bash
umi-ocr --reload
```

- Certains états de compatibilité de démarrage/runtime peuvent aussi impliquer :
  - `UmiOCR-data/.pre_settings`
  - `UmiOCR-data/logs/` (pour les versions avec journalisation runtime)

## Exemples

### Exemple 1 : OCR batch par chemin

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

### Exemple 4 : Invocation avancée de module

```bash
umi-ocr --all_modules
umi-ocr --call_qml QRCode --func scanPaths '["D:/Pictures/Screenshots/test/二维码/1111.png","D:/Pictures/Screenshots/test/二维码/2222.png"]'
```

## Références API

- Manuel ligne de commande : [docs/README_CLI.md](docs/README_CLI.md)
- Manuel API HTTP : [docs/http/README.md](docs/http/README.md)
- API OCR : [docs/http/api_ocr.md](docs/http/api_ocr.md)
- API Document : [docs/http/api_doc.md](docs/http/api_doc.md)
- API QR : [docs/http/api_qrcode.md](docs/http/api_qrcode.md)
- Bridge HTTP argv : [docs/http/argv.md](docs/http/argv.md)

## Notes de développement

- Points d'entrée :
  - `UmiOCR-data/main.py` (bootstrap runtime)
  - `UmiOCR-data/py_src/run.py` (démarrage de l'application)
- Stack UI : PySide2 + QML (`UmiOCR-data/qt_res/qml`).
- Services cœur :
  - `py_src/server/*` pour HTTP + transport de commandes
  - `py_src/mission/*` pour les tâches OCR/Doc/QR en file d'attente
  - `py_src/ocr/*` pour le post-traitement OCR et les sorties
- Moteurs OCR pris en charge par l'écosystème :
  - [PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json)
  - [RapidOCR-json](https://github.com/hiroi-sora/RapidOCR-json)
- Framework runtime : [PyStand (customized)](https://github.com/skywind3000/PyStand)

## Dépannage

Pour les détails complets de dépannage : https://github.com/hiroi-sora/Umi-OCR/issues/447

Index rapide :

| Symptôme | Aller à |
| --- | --- |
| Impossible de trouver `Py_Main()` | [`Cannot find Py_Main()`](#cannot-find-py_main) |
| Échec de création du contexte OpenGL | [`Failed to create OpenGL context`](#failed-to-create-opengl-context) |
| L'application plante au démarrage | [`Umi-OCR.exe has stopped working`](#umi-ocrexe-has-stopped-working) |
| `0xc0000142` / échec init OCR | [`0xc0000142` or OCR init failure with MKLDNN/AVX hints](#0xc0000142-or-ocr-init-failure-with-mkldnnavx-hints) |
| `api-ms-win-crt-runtime-l1-1-0.dll` manquant | [`Missing api-ms-win-crt-runtime-l1-1-0dll`](#missing-api-ms-win-crt-runtime-l1-1-0dll) |

### `Cannot find Py_Main()`

- Installez le runtime VC : https://aka.ms/vs/17/release/vc_redist.x64.exe
- Ou lancez avec le fallback `UmiOCR-data/RUN_GUI.bat`.
- Note : le lanceur `.bat` a des limitations (pas de contrôle CLI, automatisation de raccourcis limitée).

### `Failed to create OpenGL context`

- Téléchargez le patch runtime : https://github.com/hiroi-sora/Umi-OCR_v2/files/13167436/opengl32sw_64.zip
- Placez la DLL extraite dans `UmiOCR-data/site-packages/PySide2/`.

### `Umi-OCR.exe has stopped working`

- Fréquent après réutilisation de config entre différentes versions de Windows.
- Supprimez `UmiOCR-data/.pre_settings` puis réessayez.

### `0xc0000142` or OCR init failure with MKLDNN/AVX hints

- Le CPU ne prend probablement pas en charge AVX.
- Utilisez la variante RapidOCR ou basculez depuis le plugin PaddleOCR :
  - [Umi-OCR_Rapid releases](https://github.com/hiroi-sora/Umi-OCR/releases)
  - [Umi-OCR plugins](https://github.com/hiroi-sora/Umi-OCR_plugins/releases)

### Console noire avec `OSError` (programme introuvable)

- Fréquent sur les premières versions non patchées de Windows 7 (notamment sans `KB2533623`).
- Correctif recommandé : exécuter Windows Update complet puis redémarrer.

### Plantage pendant l'export PDF recherchable

- Souvent causé par des mises à jour Windows 7 manquantes (notamment `KB4534310` et dépendances).
- Correctif recommandé : installer toutes les mises à jour système manquantes via Windows Update.

### `api-ms-win-crt-runtime-l1-1-0.dll` manquant

- Installez le runtime VC : https://aka.ms/vs/17/release/vc_redist.x64.exe

### Placement manuel des raccourcis

Si la création automatique des raccourcis échoue, placez-les manuellement :

- Menu Démarrer : `C:\ProgramData\Microsoft\Windows\Start Menu`
- Démarrage : `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup`

## Localisation

Ce projet utilise Weblate pour la localisation collaborative :

- [Weblate: Umi-OCR](https://hosted.weblate.org/engage/umi-ocr/)

Fichiers README de langue dans ce dépôt :

| Langue | Fichier |
| --- | --- |

Merci à tous les traducteurs :

| Traducteur | Langues contribuées |
| --- | --- |
| [杨鹏](https://hosted.weblate.org/user/ypf) | Português |
| [தமிழ்நேரம்](https://hosted.weblate.org/user/TamilNeram/) | தமிழ் |

S'il y a des erreurs ou des omissions, veuillez répondre dans [cette discussion](https://github.com/hiroi-sora/Umi-OCR/discussions/449).

## Roadmap

### Terminé

- Architecture par pages d'onglets.
- Contrôleur OCR API.
- Contrôleur des missions/tâches OCR.
- Gestionnaire de thème avec prise en charge clair/sombre.
- OCR batch.
- OCR par capture d'écran.
- Mécanisme de raccourcis clavier.
- Menu de zone de notification.
- Post-traitement des blocs de texte (optimisation de mise en page).
- Nettoyage mémoire du moteur.
- UI multilingue.
- Mode ligne de commande.
- Compatibilité Windows 7.
- Format de sortie Excel (CSV).
- Interruption `Esc` pour la capture d'écran.
- Fichiers de thème externes.
- Changement de police.
- Animation de chargement.
- Régions à ignorer.
- Reconnaissance QR code.
- Aperçu d'image en reconnaissance batch.
- Reconnaissance PDF.
- Ouvrir l'image avec un visualiseur local. [#335](https://github.com/hiroi-sora/Umi-OCR/issues/335)
- Répéter la zone de capture précédente. [#357](https://github.com/hiroi-sora/Umi-OCR/issues/357)
- Correction du problème de compatibilité Windows 7 dans la reconnaissance de documents.
- Prise en charge lecture/création QR dans les interfaces HTTP et CLI. (#423)
- Documentation de l'interface QR.
- Migration vers la plateforme Linux.
- API HTTP de reconnaissance de documents.

### Plans à long terme

Les éléments suivants sont des idées planifiées et peuvent évoluer pendant le développement :

- [ ] Refactoriser le mécanisme de plugin sous-jacent.
- [ ] Plugin d'API OCR en ligne.
- [ ] Plugin indépendant de reconnaissance de formules.
- [ ] Onglet dédié aux formules avec rendu LaTeX.
- [ ] Mécanisme de vérification des mises à jour.
- [ ] Modules de post-traitement supplémentaires au-delà de l'analyse de mise en page.
- [ ] Déclencheurs d'événements pour les fonctions clés de l'interface.
- [ ] OCR hors ligne basé GPU.
- [ ] Traduction d'image.
- [ ] Traduction hors ligne.
- [ ] OCR de région fixe.
- [ ] Reconnaissance de tableaux vers sortie Excel.
- [ ] Système d'historique.
- [ ] Extension de compatibilité à des plateformes comme macOS/Ubuntu.

## Contribution

Les contributions sont bienvenues.

- Signalez des bugs ou demandez des fonctionnalités via [Issues](https://github.com/hiroi-sora/Umi-OCR/issues).
- Discutez des idées dans [Discussions](https://github.com/hiroi-sora/Umi-OCR/discussions).
- Contribuez aux traductions via [Weblate](https://hosted.weblate.org/engage/umi-ocr/).
- Pour le travail sur les moteurs/plugins, voir aussi [Umi-OCR_plugins](https://github.com/hiroi-sora/Umi-OCR_plugins).

Pour l'environnement de développement, suivez les dépôts runtime de plateforme :

- [Umi-OCR_runtime_windows](https://github.com/hiroi-sora/Umi-OCR_runtime_windows)
- [Umi-OCR_runtime_linux](https://github.com/hiroi-sora/Umi-OCR_runtime_linux)

## Support

Umi-OCR est principalement développé et maintenu sur le temps libre par [hiroi-sora](https://github.com/hiroi-sora).

Si ce projet vous aide, un sponsor est apprécié :

- Afdian (CN) : https://afdian.com/a/hiroi-sora

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hiroi-sora/Umi-OCR&type=Date)](https://star-history.com/#hiroi-sora/Umi-OCR&Date)

## CHANGE LOG

- [CHANGE_LOG.md](CHANGE_LOG.md)

## Licence

Ce projet est distribué sous licence MIT.

- [LICENSE](LICENSE)
