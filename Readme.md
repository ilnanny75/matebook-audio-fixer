<p align="center">
  <img src="logo.png" width="200" alt="MateBook Audio Fixer Logo">
</p>

# 🎧 MateBook Audio Fixer (ES8336)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![OS: Debian | Arch](https://img.shields.io/badge/OS-Debian%20%7C%20Arch-orange.svg)](https://www.linux.org/)

Un tool interattivo per ripristinare l'audio sui laptop con chip **Everest ES8336**. Testato su Huawei MateBook, Chuwi e Teclast.

---

## 🌍 Istruzioni Multilingua / Multilingual Guide

### 🇮🇹 Italiano
Risolve il problema dell'audio "muto" configurando i driver SOF e i file UCM su Debian (MX Linux, Ubuntu) e Arch Linux.
1. `git clone https://github.com/ilnanny75/matebook-audio-fixer.git`
2. `cd matebook-audio-fixer && chmod +x matebook-audio-fixer.sh`
3. `./matebook-audio-fixer.sh`

### 🇬🇧 English
Fixes the "no sound" issue by configuring SOF drivers and UCM files on Debian-based and Arch-based distros.
1. `git clone https://github.com/ilnanny75/matebook-audio-fixer.git`
2. `cd matebook-audio-fixer && chmod +x matebook-audio-fixer.sh`
3. `./matebook-audio-fixer.sh`

### 🇫🇷 Français
Corrige les problèmes audio de l'ES8336 sur les distributions basées su Debian et Arch.
1. Clonez le dépôt e rendez lo script exécutable.
2. Lancez `./matebook-audio-fixer.sh`.

### 🇪🇸 Español
Soluciona los problemas de audio del chip ES8336 en distribuciones basadas en Debian y Arch.
1. Clonar el repositorio y dar permisos de ejecución.
2. Ejecutar `./matebook-audio-fixer.sh`.

### 🇩🇪 Deutsch
Behebt ES8336-Audioprobleme auf Debian- und Arch-basierten Distributionen.
1. Repository klonen und Skript ausführbar machen.
2. `./matebook-audio-fixer.sh` ausführen.

---

## 🛠️ Cosa fa lo script? / Technical details
* **Firmware:** Installa `firmware-sof-signed` (Debian) o `sof-firmware` (Arch).
* **Kernel Fix:** Aggiunge `snd_intel_dspcfg.dsp_driver=3` ai parametri di avvio del GRUB.
* **ALSA UCM:** Verifica e mappa le vie audio corrette per il chip Everest ES8336.

---

## 📄 Licenza / License
Distribuito sotto licenza **GPLv3**. Maggiori informazioni nel file [LICENSE](LICENSE).
