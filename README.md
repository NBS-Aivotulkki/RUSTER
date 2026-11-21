# RUSTER
**Rusted. Busted. Loud.**

RUSTER is a deliberately filthy guitar distortion effect inspired by broken amplifiers, rough transistor saturation and loose metallic hardware rattling against a speaker.

## RUSTER 0.4.5 Beta — Free download

**[Download the latest beta release](https://github.com/NBS-Aivotulkki/RUSTER/releases)**

The first beta is built for **Intel Macs (x86_64)** and includes:
- **AU (Audio Unit)** for GarageBand and Logic Pro
- **VST3** for compatible DAWs

It is an audio effect, not a standalone instrument. **Apple Silicon compatibility has not been verified.** This beta has **not been verified as Developer ID-signed or Apple-notarized**, so macOS may block installation. Do not disable system-wide security protections to install it.

> **Note:** The beta download will appear at the link above once the first GitHub Release has been published.

## Controls

| Control | What it does |
| --- | --- |
| DRIVE | Saturation intensity |
| RUST | Broken, asymmetric, tearing distortion |
| SAG | Amp-like compression and dynamic sag |
| JUNK | Metal-on-metal rattle that follows the note's attack and decay |
| ZEST | Bite and brightness, with extreme top-end boost |
| CUT | Noise gate |
| BLEND | Dry/wet mix |
| BLAST | Output level |

## Installation (macOS)

1. Download the **macOS Intel ZIP** from **Releases**.
2. Quit GarageBand, Logic Pro, or your other DAW, then extract the complete ZIP.
3. Open **Terminal**, type `bash ` (including the space), drag `Install_RUSTER.command` from the extracted folder into Terminal, and press Return.
4. Restart your DAW. In GarageBand or Logic, look under **Audio Units → Ruster Audio → RUSTER**.

Manual installation paths:
- AU: `~/Library/Audio/Plug-Ins/Components/`
- VST3: `~/Library/Audio/Plug-Ins/VST3/`

## Beta feedback

Please open a [GitHub issue](https://github.com/NBS-Aivotulkki/RUSTER/issues) with your Mac type (Intel or Apple Silicon), macOS version, DAW, reproduction steps, and a description of the sound or behavior.

## License and status

**Free beta; proprietary software. All rights reserved.** Source code is not published in this repository. Downloading the beta does not grant permission to redistribute, modify or reverse-engineer the software beyond rights provided by applicable law. The software is provided for evaluation without warranty, to the extent permitted by applicable law.
