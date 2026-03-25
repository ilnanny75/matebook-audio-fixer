# 🎧 MateBook Audio Fixer (ES8336)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![OS: Debian | Arch](https://img.shields.io/badge/OS-Debian%20%7C%20Arch-orange.svg)](https://www.linux.org/)

Un script Bash interattivo per risolvere il problema dell'audio sui laptop con chip **Everest ES8336** (Huawei MateBook, Chuwi, Teclast, ecc.) su Linux.

---

## 🌍 Multilingual Instructions

### 🇮🇹 Italiano
Script per configurare i driver SOF e i file UCM. Supporta Debian (MX Linux, Ubuntu) e Arch Linux.
1. `git clone https://github.com/ilnanny75/matebook-audio-fixer.git`
2. `cd matebook-audio-fixer && chmod +x matebook-audio-fixer.sh`
3. `./matebook-audio-fixer.sh`

### 🇬🇧 English
Interactive script to fix ES8336 audio issues on Debian-based and Arch-based distros.
1. `git clone https://github.com/ilnanny75/matebook-audio-fixer.git`
2. `cd matebook-audio-fixer && chmod +x matebook-audio-fixer.sh`
3. `./matebook-audio-fixer.sh`

### 🇫🇷 Français
Script interactif pour corriger les problèmes audio de l'ES8336.
1. Clonez le dépôt et rendez lo script exécutable.
2. Exécutez `./matebook-audio-fixer.sh` et suivez le istruzioni.

### 🇪🇸 Español
Script interactivo para solucionar problemas de audio del chip ES8336.
1. Clonar el repositorio y dar permisos de ejecución.
2. Ejecutar `./matebook-audio-fixer.sh`.

### 🇩🇪 Deutsch
Interaktives Skript zur Behebung von ES8336-Audioproblemen.
1. Repository klonen und Skript ausführbar machen.
2. `./matebook-audio-fixer.sh` ausführen.

---

## 🛠️ Technical Details
Lo script agisce su:
* **Firmware:** Installa `firmware-sof-signed` (Debian) o `sof-firmware` (Arch).
* **Kernel:** Aggiunge `snd_intel_dspcfg.dsp_driver=3` al GRUB.
* **UCM:** Verifica la presenza delle mappe ALSA in `/usr/share/alsa/ucm2/`.

---

## 📄 License
This project is licensed under the **GPLv3 License** - see the [LICENSE](LICENSE) file for details.
