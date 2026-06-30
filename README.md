# 🎧 Resonāda

### A high-fidelity, bit-perfect music player for Android — built for people who hear the difference.

[![Latest release](https://img.shields.io/github/v/release/kaurav99/audiophiles-dream?style=for-the-badge&label=Download&color=E0B567)](https://github.com/kaurav99/audiophiles-dream/releases/latest)
[![Total downloads](https://img.shields.io/github/downloads/kaurav99/audiophiles-dream/total?style=for-the-badge&color=6FB7B0)](https://github.com/kaurav99/audiophiles-dream/releases)
[![Platform](https://img.shields.io/badge/Platform-Android%2011%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](#-install)
[![Telegram](https://img.shields.io/badge/Telegram-Join%20the%20group-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/+urRX_WELImQ0MjU1)
[![License](https://img.shields.io/badge/License-Freeware-blue?style=for-the-badge)](#-license)

**[⬇️ Download the latest APK](https://github.com/kaurav99/audiophiles-dream/releases/latest)**

</div>

---

## ✨ Overview

**Resonāda** is a no-compromise local music player for Android that treats your
audio chain with the respect it deserves. From **Bit Xact USB DAC output** to a real-time
**signal-path inspector**, it’s designed for listeners who care about *how* their music sounds —
not just what’s playing.

> Drop in your lossless library, plug in your DAC, and let the bits flow untouched.

---

## 🌟 Features

### 🔊 Sound quality first
- **Bit Xact output** — bit-for-bit playback that bypasses the system mixer for an unaltered signal, with a live badge that tells the truth about the whole path (DSP, software volume and DAC clock).
- **Exclusive USB DAC output** — a native USB Audio driver streams straight to your DAC, bit-for-bit, with sample-rate matching. Lossless *and* lossy formats (FLAC, ALAC, WAV, AIFF, MP3, AAC/M4A, Ogg/Vorbis, Opus) all take the native path.
- **Native DSD / DoP** — DSF and DFF up to your DAC's limits.
- **Live signal-path inspector** — see exactly what happens between the file and your ears, including real-time USB stream health.
- **High-res aware** — reads and displays sample rate, bit depth, bitrate and codec straight from the file.

### 🎚️ Universe DSP
- **Up to 32-band parametric EQ** with true RBJ filters and click-free coefficient ramping.
- **Convolution** (impulse-response) for headphone & room correction, **crossfeed**, and **compressor / limiter** dynamics.
- **AutoEQ, built in** — import oratory1990 / Crinacle profiles, or search the headphone-correction catalogue in-app and apply with one tap.
- **Colourful response curve** and a real-time spectrum analyser.

### 📊 Insight
- **Fidelity Analysis & scoring** — TT DR dynamic range, True Peak (dBTP) and integrated loudness (LUFS), graded Poor → Reference.
- **BPM & musical-key detection** for any track, including DSD.

### 📚 Library & metadata
- Fast **incremental** on-device scan that updates only what changed, with SD-card and multi-folder support.
- **In-app folder browser** to add any folder — including Music — without fighting Android's system picker.
- **Online metadata + cover art** — fetch and write tags back, or embed / save a folder cover every player reads.
- **Synced lyrics** with word-level timing, on screen and in the playback notification.
- **Update on launch** — one-tap updates for side-loaded installs.

### ☁️ Connected
- Stream from **WebDAV**, **Dropbox**, **DLNA / UPnP** servers and **SoundCloud**.
- Act as a **UPnP / DLNA renderer and media server** on your network.
- **Last.fm** and **ListenBrainz** scrobbling with configurable thresholds, plus listening **statistics & insights**.

### 🎨 Crafted experience
- **5 selectable launcher icons** whose gradient flows into the in-app accents.
- A premium, animated **“Spanda Bindu” cosmic-dance** About screen — tap to sound the Oṃ.
- Clean Material 3 dark theme with green/red status feedback throughout.

---

## 📲 Install

> Requires **Android 11 (API 30)** or newer.

1. Open the **[latest release](https://github.com/kaurav99/audiophiles-dream/releases/latest)** and download the `.apk`.
2. On your phone, tap the downloaded file.
3. If prompted, allow **“Install unknown apps”** for your browser/file manager.
4. Tap **Install**, then open **Resonāda**.
5. Grant audio/storage access so it can scan your library.

The APK is **signed**; updates with the same signature install over the top without data loss.

---

## 📸 Screenshots


|     Playing      |      Cloud       |   Spectrogram    |    Equalizer     |
| :--------------: | :--------------: | :--------------: | :--------------: |
| <img src="https://github.com/user-attachments/assets/415a21b7-a582-4233-ae43-7d2c49bbf4c9" width="180"> | <img src="https://github.com/user-attachments/assets/b915e856-8e29-4620-8171-17f7dfa29dd7" width="180"> | <img src="https://github.com/user-attachments/assets/14731fdd-8f66-441f-9f0d-8c441610557d" width="180"> | <img src="https://github.com/user-attachments/assets/4ac4c7ca-8fcf-432a-9114-e772b1b8f92c" width="180"> |

|     Analyze      |      Lyrics      |      Stats       |     Settings     |
| :--------------: | :--------------: | :--------------: | :--------------: |
| <img src="https://github.com/user-attachments/assets/6b8dc4e0-176c-4666-8a74-e4ccf99735e0" width="180"> | <img src="https://github.com/user-attachments/assets/f6c6a447-fdc4-4e81-9ded-8d56e42467af" width="180"> | <img src="https://github.com/user-attachments/assets/796356ec-80d6-41b9-b526-af96acfa9170" width="180"> | <img src="https://github.com/user-attachments/assets/ebb16f08-f321-4f78-87e3-f74c02b879e7" width="180"> |

|      About       |
| :--------------: |
| <img src="https://github.com/user-attachments/assets/32915c40-47ff-4b65-851f-be55753b36eb" width="180"> |


---

## 🗒️ Releases

All builds are published on the **[Releases](https://github.com/kaurav99/audiophiles-dream/releases/latest)** page,
with notes describing what changed. The current line is **`1.0.0 · Purna · whole`**.

---

## ❓ FAQ

**Is the source code available?**
This repository distributes the official signed builds. The source is maintained privately.

**Why does it need permissions?**
Audio/storage access is used solely to scan and play your local library. Nothing is uploaded.

**Will it work with my USB DAC?**
Most UAC-compliant USB DACs are supported for exclusive, bit-perfect output.

---


## 💬 Community

Join the **[Resonāda Telegram group](https://t.me/+urRX_WELImQ0MjU1)** for release
announcements, early builds, help and feedback — and to share what your DAC is doing.

---


## 📜 License

**© 2026 R Kaurav. All rights reserved.**

Resonāda is **proprietary freeware** — free to download and use for
personal, non-commercial listening, but it is **not** open source.

You **may**:
- Install and use the official signed builds on your own devices, at no cost.
- Share a link to the [Releases page](https://github.com/kaurav99/audiophiles-dream/releases).

You **may not**:
- Decompile, reverse-engineer, modify, or create derivative works of the app.
- Redistribute, rehost, or sell the APK or any part of it.
- Use the name, icons, or assets without written permission.

The software is provided **"as is", without warranty of any kind**, express or
implied. The author is not liable for any damages arising from its use.

Third-party open-source components are used under their respective licenses
(e.g. the bundled Apple ALAC decoder under the Apache License 2.0). The full
list of components and their notices is available in-app under
**Settings → About → Open-source licenses**.

For any other use, contact the author at **ralkau@proton.me**.

---

<div align="center">

**Resonāda** — _the vibrating point of origin._

Made with care by **R Kaurav**.

<sub>Keywords: audiophile android music player · bit-perfect · USB DAC · hi-res audio · FLAC · lossless · exclusive output · parametric EQ · DSP · synced lyrics · Last.fm · ListenBrainz · SoundCloud</sub>

</div>
