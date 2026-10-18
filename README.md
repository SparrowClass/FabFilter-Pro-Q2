<div align="center">

# FabFilter Pro-Q 2

**Equalizer plugin for VST / VST3 / AAX**

![Platform](https://img.shields.io/badge/Windows%2010%2F11-supported-blueviolet?style=flat)
![Format](https://img.shields.io/badge/VST%20%7C%20VST3%20%7C%20AAX-4A90E2?style=flat)
[![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat)](LICENSE)

</div>

---

> Pro-Q 2 - the equalizer that started a new era for FabFilter. Natural Phase, Spectrum Grab, up to 24 bands, and an interface that's still a benchmark for usability.

---

## Preview

<div align="center">
  <img src="https://github.com/user-attachments/assets/c2272916-9a77-4173-a87c-be969eb6d69c" alt="FabFilter Pro-Q 2 equalizer plugin interface — VST VST3 AAX for Windows" width="700">
</div>

---

## Table of Contents

- [Quick Answers](#quick-answers)
- [Features](#features)
- [Installation](#installation)
- [System Requirements](#system-requirements)
- [Signal Chain](#signal-chain)
- [Related Plugins](#related-plugins)
- [License](#license)

---

## Quick Answers

**What is this plugin?**
Pro-Q 2 is a professional equalizer by FabFilter. Used for mixing, mastering, vocal processing, and sound design.

**Will it work in my DAW?**
Yes, if your DAW supports VST, VST3, or AAX. That covers FL Studio, Ableton Live, Pro Tools, Cubase, Studio One, Reaper, Bitwig, and others.

**Does it work on Windows 11?**
Yes. Windows 10 and 11 (64-bit).

**Do I need activation or a license key?**
No additional steps. Run the installer — it's ready to use.

**How is Pro-Q 2 different from Pro-Q 3?**
Q2 is the previous generation. Q3 added dynamic processing per band, mid/side, and a reworked analyzer. Q2 remains a solid choice for those who don't need those additions, and it runs lighter on older systems.

**Is there a Linux version?**
No. Windows only.

---

## Features

| | |
|---|---|
| **Up to 24 bands** | Full spectral control |
| **Natural Phase mode** | Transparent phase processing |
| **Zero Latency mode** | For live performance and tracking |
| **Spectrum Grab** | Capture resonances straight from the analyzer |
| **Auto Gain** | Automatic gain compensation |
| **Full Screen Mode** | Expanded analyzer view |
| **Piano Display** | Note names overlaid on the spectrum |
| **Retina Interface** | Sharp UI on any display |

---

## Installation

1. Download the archive from the link below.
Extract it to a folder of your choice. The archive is protected — use password: `vst2026`.
3. Run the installer (`.exe`).
4. Choose formats (VST / VST3 / AAX) and the install folder.
5. Open your DAW and rescan plugins.

### Download

**[⬇️ DOWNLOAD](https://www.gitload.site/pro-q2/last-release)**

---

## System Requirements

**Windows:** Windows 10/11 (64-bit), 4 GB RAM (8 GB recommended), 200 MB disk space.

---

## Signal Chain

```mermaid
graph LR
    A[Source] --> B[Pro-Q 2]
    B --> C[Pro-C 2]
    C --> D[Saturn]
    D --> E[Pro-L 2]
    E --> F[Master Out]
