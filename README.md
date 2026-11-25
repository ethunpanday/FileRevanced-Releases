# ⚡ FileRevanced

<p align="center">
  <b>Inspired by File Pilot — an advanced, high-performance Windows file manager engineered with Modern C++20, Direct3D 11 acceleration, Floating Drop Shelf, Android ADB Share &amp; Scrcpy Screen Sharing, virtual archives, and refined desktop precision.</b>
</p>

<p align="center">
  <a href="https://github.com/ethunpanday/FileRevanced-Releases/releases/latest"><img src="https://img.shields.io/github/v/release/ethunpanday/FileRevanced-Releases?include_prereleases&color=0078D4&label=Latest%20Version&logo=github" alt="Latest Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-0078D7?logo=windows11" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/Type-Portable%20%26%20Standalone-41CD52?logo=files" alt="Type"></a>
  <a href="#"><img src="https://img.shields.io/badge/Architecture-x86__64-orange" alt="Architecture"></a>
  <a href="https://github.com/ethunpanday/FileRevanced-Releases/issues"><img src="https://img.shields.io/github/issues/ethunpanday/FileRevanced-Releases?color=purple" alt="Issues"></a>
</p>

<p align="center">
  <img src="preview.png" alt="FileRevanced Preview" width="900" />
</p>

> [!NOTE]
> **Inspired by File Pilot**, FileRevanced brings blazing-fast C++20 / Direct3D 11 responsiveness to Windows while adding power features built right in — including **Floating Drop Shelf**, **Android ADB USB & Wi-Fi Transfer**, **Screen Sharing (`scrcpy`)**, **Smartphone Backup**, **Virtual Archive Explorer**, and **Inline Video & PDF Previews**.

---

## 📥 Downloads

### 🚀 Official Standalone Executable
Get the latest official standalone release below:

| Package | Version | Type | Size | Download |
| :--- | :--- | :--- | :--- | :--- |
| **`FileRevanced.exe`** | `v0.1.0 Beta` | Standalone Executable (Portable) | ~12.5 MB | [**Download Latest (v0.1.0 Beta)**](https://github.com/ethunpanday/FileRevanced-Releases/releases/latest) |

> [!TIP]
> **No installation required!** `FileRevanced.exe` is completely portable and self-contained. Simply download and double-click to run. If you prefer system-wide integration (`Win + E`, Default Explorer, context menus) or pre-downloading optional **ADB** and **SCRCPY** tools, you can configure everything in Setup with one click.

👉 **[View all Releases & Changelogs](https://github.com/ethunpanday/FileRevanced-Releases/releases)**

---

## ✨ Key Highlights

### ⚡ Core Performance & File Engine
- **Native Hardware Speed**: Built with Modern C++20 and Direct3D 11-accelerated Qt 6 UI for crisp high-refresh-rate rendering (`60 / 120 / 144Hz+`).
- **Turbo Ping-Pong I/O Transfer Engine**: Multi-threaded small-file pool + 4 MB double-buffered async overlapped I/O for large files, live throughput chart, disk-space pre-checks, `.part` atomic safe-writes, and per-file conflict resolution (`Popup`, `Auto-Rename`, `If Newer`, `Overwrite`, `Skip`).
- **Single Compact Standalone**: UI engine, styles, and compressed LZMA2 payload bundled into a single ~12.5 MB executable with zero runtime dependencies.
- **Built-In Storage Benchmark**: Test sequential read/write, random 4K IOPS, and USB generation speed detection directly inside the app.

### 📱 Android Integration (ADB + Scrcpy)
- **Android Transfer (ADB USB & Wi-Fi)**:
  - High-speed USB and Wireless ADB transfers (up to 15× faster than Windows MTP) with accurate engine telemetry (`ADB USB` / `ADB Wi-Fi`).
  - Built-in **QR Code Pairing**, **6-Digit Pairing Code**, **Connect by IP**, paired endpoint history, and interactive ADB Setup Guide.
  - **True Pause & Byte-Offset Resume**: Pausing an ADB transfer immediately halts the socket with zero background buffering and resumes cleanly from the exact byte offset (`dd` byte-range stream) without losing progress.
- **Screen Sharing (`scrcpy`)**:
  - Mirror, control, or record your Android screen over USB or ADB Wi-Fi directly from FileRevanced.
  - Compact controls for **Mode** (`Screen`, `Virtual Display`, `Back Camera`, `Front Camera`, `Audio Only`), **Resolution**, **Bitrate**, **Frame Rate** (up to 120 FPS), **Codec** (`H.264`, `H.265`, `AV1`), **Rotation**, **Audio**, and two-column toggle switches with `(?)` hover tooltips.
- **Smartphone Backup & Media Organiser**: Guided phone backup over ADB/MTP and one-click photo/video organization.
- **Smart On-Demand Tool Downloads**: Choose whether to download **ADB** and **SCRCPY** during installation, or keep setup minimal—if either tool is missing or removed later, FileRevanced displays a compact in-app prompt to download it automatically when needed.

### 🗂️ Workspace, Archives & Previews
- **Split Panes, Unlimited Tabs & Drag-and-Drop**: Dual-pane workspace, tab context menus, native Windows Explorer-style drag icon previews with count badges, dynamic `Move to` / `Copy to` drop badges, sidebar drive/folder drop targets, and a **Floating Drop Shelf** (circle-to-popup staging tray for cross-pane/cross-folder transfers).
- **Virtual Archive Explorer**: Browse inside `.zip`, `.7z`, `.rar`, `.tar`, and other archives natively like regular folders, add/drag files out, and handle **password-protected archives** seamlessly.
- **Inline Inspector & Rich Previews**:
  - **Inline Video Player**: Hardware-backed Media Foundation playback with seekbar, volume, fullscreen-free inline floating details overlay, and hover timeline thumbnails.
  - **Multi-Page PDF Reader**, high-res image viewer, syntax-highlighted code/text preview, and live resizable columns with divider drag & double-click reset.
- **Instant Asynchronous Search & Explorer Replacement**: Real-time filtering, fuzzy search, expandable tree navigation, optional `Win + E` hijack, right-click shell context menus, obsidian dark/light Fluent themes, UI scaling presets, and an in-app **Auto-Updater & Changelog viewer**.

---

## 🛠️ Getting Started

### Mode 1: Portable / Standalone
1. Download **`FileRevanced.exe`** from the [Latest Release](https://github.com/ethunpanday/FileRevanced-Releases/releases/latest).
2. Place it anywhere (e.g. `Downloads`, `Desktop`, or a USB drive).
3. Double-click to launch and start immediately.

### Mode 2: System Installation (Optional)
To integrate FileRevanced deeply into Windows:
1. Open **FileRevanced**.
2. Click **Menu** $\rightarrow$ select **Setup**.
3. Configure your integration toggles & optional downloads:
   - **Desktop shortcut** — Add a shortcut to your Desktop.
   - **Set as default** — Register `Win + E` and default folder launches.
   - **Right-click entries** — Add "Open in FileRevanced" to folders & drives.
   - **Add to PATH** — Launch `file-revanced` directly from CMD or PowerShell.
   - **Download Additional Files (`ADB` / `SCRCPY`)** — Pre-download Google Platform Tools and Scrcpy during install (or uncheck either one and download on demand later).
4. Click **Install / Apply Changes**.

---

## 🔄 Updates

FileRevanced features a built-in update & changelog client:
1. Inside FileRevanced, go to **Menu** $\rightarrow$ **Setup** (or **Changelog**).
2. Click **Check for Updates**:
   - FileRevanced checks this repository for newer releases.
   - If an update is available, click **Update** to download and apply it automatically while preserving your settings.

---

## 💻 System Requirements

| Component | Minimum Requirement | Recommended |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit, 1809+) | Windows 11 (64-bit, 22H2+) |
| **Architecture** | x86_64 (64-bit) | x86_64 (64-bit) |
| **Graphics** | DirectX 11 compatible GPU / iGPU | Dedicated GPU with Direct3D 11 support |
| **Memory** | 512 MB RAM | 2 GB+ RAM |
| **Disk Space** | ~35 MB free space | 100 MB+ free space (extra if ADB/Scrcpy downloaded) |

---

## 🐛 Issues & Feedback

Found a bug or have a feature request?
We welcome feedback and contributions! Please open an issue on the issue tracker:
👉 **[Report an Issue / Request Feature](https://github.com/ethunpanday/FileRevanced-Releases/issues)**

---

## 📄 License & Credits

- Developed & Maintained by **Ethun Panday**
- Built with **Modern C++20**, **Qt Quick (Qt 6)**, **Direct3D 11**, and **Windows Media Foundation**
- Powered optionally by Google **Android Platform Tools (ADB)** & **Genymobile `scrcpy`**
- Release Hub: [FileRevanced-Releases](https://github.com/ethunpanday/FileRevanced-Releases)
