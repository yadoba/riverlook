# RiverLook

**Flow through every photo. Instant, lightweight image viewing and conversion in pure Rust by Yadoba Studio.**

[![Official Website](https://img.shields.io/badge/website-riverlook.yadoba.com-00b4d8?style=for-the-badge)](https://riverlook.yadoba.com)
[![Download Latest](https://img.shields.io/badge/downloads-Releases%20v0.8.5-0077b6?style=for-the-badge)](https://github.com/yadoba/riverlook/releases)
[![Interactive 3D Demo](https://img.shields.io/badge/try_online-Live%20WASM%20Demo-48cae4?style=for-the-badge)](https://riverlook.yadoba.com/#demo)
[![License](https://img.shields.io/badge/license-Freeware-101622?style=for-the-badge)](LICENSE)

RiverLook is a high-performance cross-platform photo viewer and image converter built with native Rust. Designed from the ground up for speed, simplicity, and visual delight, RiverLook delivers instant ~15 ms cold starts, built-in mobile codec decoding without Microsoft Store add-ons, and mesmerizing 3D gallery views.

---

## ⚡ Key Highlights

- **⚡ Instant Launches (~15 ms):** Native hardware-accelerated rendering (`OpenGL` / `Glow`) with zero Electron or WebView2 bloat.
- **📱 Built-In iPhone HEIC Support:** Decode `.heic` and `.heif` camera captures out-of-the-box with multi-threaded performance.
- **🌊 4 Interactive 3D Gallery Looks:**
  - **Whale Look:** Majestic ocean whale silhouette with conveyor streaming from flukes to mist spray.
  - **River Look:** Harmonic harmonic river wave stream with drifting particles.
  - **Hyper Star Look:** High-speed cosmic crawl with multi-lane depth streaks.
  - **Sphere Look:** Fibonacci sphere distributing photos across a 3D celestial globe.
- **🔄 One-Click Format Conversion:** Batch convert or export single images between modern formats (`JPEG`, `PNG`, `WebP`, `AVIF`, `HEIC`, `BMP`, `TIFF`).
- **📋 On-Demand EXIF Inspector:** Press <kbd>I</kbd> to inspect camera settings, shutter speed, ISO, focal length, lens model, and copyable EXIF metadata.
- **🛡️ 100% Offline & Private:** Zero telemetry, zero analytics tracking, and zero internet calls. Your photos stay strictly on your device.

---

## 📥 Downloads & Installation

Prebuilt standalone binaries are published for **Windows**, **Linux**, and **macOS** on our [Releases Page](https://github.com/yadoba/riverlook/releases/latest) and the [RiverLook Website](https://riverlook.yadoba.com).

### Windows 10 / 11 (64-bit)

- **Setup Wizard Installer:** [`riverlook-windows-x86_64-setup.exe`](https://github.com/yadoba/riverlook/releases/latest/download/riverlook-windows-x86_64-setup.exe)
  - Full graphical setup wizard.
  - Start Menu and Desktop shortcuts.
  - Windows 11 Explorer right-click context menu (*"Open with RiverLook"*).
  - Shell thumbnail provider for 22 image formats.
- **Portable Zip Archive:** [`riverlook-windows-x86_64.zip`](https://github.com/yadoba/riverlook/releases/latest/download/riverlook-windows-x86_64.zip)
  - Zero-install portable bundle. Extract and run `riverlook.exe` from any folder or USB drive.

### Linux (x86_64)

- **Prebuilt Archive:** [`riverlook-linux-x86_64.tar.gz`](https://github.com/yadoba/riverlook/releases/latest/download/riverlook-linux-x86_64.tar.gz)
  - Native Wayland & X11 support with automatic desktop integration.
  - Tested on openSUSE (Tumbleweed / Leap), Ubuntu 22.04+, Fedora 38+, and Arch Linux.

### macOS (Apple Silicon)

- **Apple Silicon (M1-M4):** [`riverlook-macos-arm64.tar.gz`](https://github.com/yadoba/riverlook/releases/latest/download/riverlook-macos-arm64.tar.gz)
  - Native Cocoa / AppKit acceleration for macOS 12 Monterey and newer.

---

## 🎨 Supported Image Formats

| Category | Extensions |
| :--- | :--- |
| **Standard Web & Photography** | `.jpg`, `.jpeg`, `.png`, `.webp`, `.gif`, `.bmp`, `.ico` |
| **Next-Gen & Mobile** | `.heic`, `.heif`, `.hif`, `.avif` |
| **High Dynamic Range (HDR)** | `.hdr`, `.exr` |
| **Professional & Print** | `.tif`, `.tiff`, `.tga`, `.qoi` |
| **Netpbm Portable Graphics** | `.pnm`, `.pbm`, `.pgm`, `.ppm`, `.pam` |

---

## 💬 Community, Support & Feedback

We welcome your feedback, ideas, and bug reports!

- **🐛 Report a Bug:** [Open an Issue](https://github.com/yadoba/riverlook/issues/new?template=bug_report.md)
- **💡 Request a Feature:** [Open a Feature Request](https://github.com/yadoba/riverlook/issues/new?template=feature_request.md)
- **✉️ Direct Studio Contact:** [riverlook@mailbox.org](mailto:riverlook@mailbox.org)

---

## 📄 License & Attribution

- **RiverLook Application:** Copyright © 2026 **Yadoba Studio** (`yadoba.com`). Released as free proprietary software (Freeware) for personal and commercial use under the [Yadoba Studio Freeware EULA](LICENSE).
- **Third-Party Open-Source Components:** Third-party libraries (including `libheif` and `libde265` under LGPL-3.0) are credited and distributed pursuant to their respective open-source licenses. For complete license texts and replacement instructions, see [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).
