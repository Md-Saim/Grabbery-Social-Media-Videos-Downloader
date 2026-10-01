<div align="center">

<img src="assets/grabbery_logo.png" alt="Grabbery Logo" width="128" height="128" style="border-radius: 28px; box-shadow: 0 8px 32px rgba(255, 45, 85, 0.35);" />

# Grabbery ⚡
### Next-Gen Universal Social Media & YouTube Media Grabber for Android

[![Latest Release](https://img.shields.io/github/v/release/Md-Saim/Grabbery---Social-Media-videos-downloader?style=for-the-badge&color=FF2D55&label=Release&logo=android)](https://github.com/Md-Saim/Grabbery---Social-Media-videos-downloader/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-00F0FF?style=for-the-badge&logo=android)](https://github.com/Md-Saim/Grabbery---Social-Media-videos-downloader/releases/latest)
[![Built With](https://img.shields.io/badge/Built%20With-Flutter%20%7C%20Dart-02569B?style=for-the-badge&logo=flutter)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-Proprietary%20%2F%20Closed%20Source-white?style=for-the-badge&logo=shield)](https://github.com/Md-Saim)
[![Developer](https://img.shields.io/badge/Developer-Moiz%20Ud%20Din%20Saim-10B981?style=for-the-badge&logo=github)](https://github.com/Md-Saim)

<p align="center">
  <b>Fast. Minimalist. Resilient. Universal.</b><br>
  Download 4K videos, MP3 audio, public YouTube playlists, Instagram Reels, TikTok videos without watermarks, and Facebook media straight to your device gallery at maximum speed.
</p>

[📥 Download Grabbery APK (v1.0.0)](https://github.com/Md-Saim/Grabbery---Social-Media-videos-downloader/releases/latest/download/Grabbery-v1.0.0-release.apk) • [✨ View Releases](https://github.com/Md-Saim/Grabbery---Social-Media-videos-downloader/releases) • [👤 Lead Developer](https://github.com/Md-Saim)

---

</div>

## 📌 Overview

**Grabbery** is a high-performance, dark-themed universal media downloader crafted with Flutter and Dart. Designed from the ground up for speed, reliability, and clean aesthetics, Grabbery completely bypasses common download issues (such as Google Video `403 Forbidden` CDN errors, missing playlist metadata, and aggressive rate limits) while maintaining a modern, zero-bloat user experience.

Unlike ad-heavy and clunky downloaders, Grabbery prioritizes:
- **Clean Architecture & UI**: Gorgeous cyberpunk dark theme with glowing neon accents and responsive micro-animations.
- **Concurrent Downloads**: Download multiple high-resolution videos and playlist tracks simultaneously, each with live progress bars and individual pause/stop/delete controls.
- **Direct Gallery Integration**: Automatically saves media to your device's standard public `Download/Grabbery` directory and notifies Android's `MediaScanner`, making all downloaded videos and songs instantly playable in Google Photos, Samsung Gallery, and system media players.

---

## 🚀 Key Features

### 🎬 YouTube 4K & MP3 Downloader
* **Zero 403 Forbidden Throttling**: Utilizes direct client stream extraction with HTTP chunk-range streaming and anti-throttling deciphering engines.
* **Format Flexibility**: Grab full 1080p/4K MP4 videos or crystal-clear 320kbps MP3 audio tracks in one tap.
* **Metadata Parsing**: Accurately fetches video title, creator, duration, and thumbnail previews before initiating download.

### 📑 Public YouTube Playlist Bulk Downloader
* **Full Playlist Extraction**: Supports standard playlists (`PL...`), music albums (`OLAK...`), channel uploads (`UU...`), mixes (`RD...`), and parameter-heavy links.
* **Resilient Multi-Tier Scraper**: Uses fallback web extraction to parse playlists even when internal YouTube API endpoints suppress channel identifiers.
* **One-Click Bulk Grab**: Download all playlist items consecutively or simultaneously with continuous progress tracking.

### 📸 Instagram Reels, Carousels & Posts
* **High-Definition Reels**: Download public Instagram Reels in original 1080p resolution with pure audio fidelity.
* **Carousel & Photo Support**: Grab multi-slide albums and single high-res images directly to your camera roll.

### 🎵 TikTok No-Watermark Downloader
* **Clean Video Streams**: Extracts clean, watermark-free HD MP4 videos from standard TikTok and Short links.
* **Original Audio Extraction**: Isolate and save TikTok background audio tracks directly.

### 👥 Facebook Video Tools
* **HD & SD Selectors**: Download public Facebook videos, reels, and clips with selectable quality profiles.

### ⚡ Concurrent Download Manager
* **Simultaneous Downloads**: Queue and download multiple media items concurrently without application freeze.
* **Interactive Control**: Pause, resume, cancel/stop, or delete active and completed downloads right from the download tray.
* **Instant Gallery Visibility**: Saves directly to `/storage/emulated/0/Download/Grabbery` and triggers Android `MediaScanner`.

---

## 📱 Screenshots Showcase

<div align="center">
<table>
  <tr>
    <td align="center" width="25%">
      <b>Home Grabber</b><br><br>
      <img src="screenshots/01_home_screen.png" alt="Home Screen" width="240" />
    </td>
    <td align="center" width="25%">
      <b>Slide-out Navigation Drawer</b><br><br>
      <img src="screenshots/02_app_drawer.png" alt="App Drawer" width="240" />
    </td>
    <td align="center" width="25%">
      <b>Playlist Bulk Downloader</b><br><br>
      <img src="screenshots/03_playlist_downloader.png" alt="Playlist Downloader" width="240" />
    </td>
    <td align="center" width="25%">
      <b>Channel Art & Tools</b><br><br>
      <img src="screenshots/04_youtube_art_tools.png" alt="Channel Art" width="240" />
    </td>
  </tr>
</table>
</div>

---

## 🛠️ Technology Stack & Engineering

Grabbery is built on a resilient cross-platform architecture optimized specifically for mobile hardware:

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Framework** | **Flutter SDK** | High-performance compiled native rendering engine (60/120 FPS). |
| **Language** | **Dart 3.x** | Sound null safety, asynchronous isolates, and stream handling. |
| **Network Engine** | **Dio + HTTP Range Chunking** | Resilient chunk-based downloader supporting streaming range requests and pause/resume states. |
| **Stream Extraction** | **Custom Native Stream Parser** | YouTube deciphering engine with anti-throttling cipher handlers to eliminate `403 Forbidden` errors. |
| **State Management** | **Provider & ChangeNotifier** | Reactive, decoupled state management for multi-task progress listeners. |
| **Storage & Gallery** | **Android MediaStore & MediaScanner** | Native Android integration for instant gallery discovery and SAF-compliant file writes. |
| **UI & Typography** | **Material 3 + Google Fonts Inter** | Minimalist obsidian theme, glassmorphic containers, and glowing neon accents. |

---

## 📥 Installation Guide

Installing **Grabbery** on your Android smartphone or tablet takes less than 30 seconds:

1. **Download the APK**: Download the latest release from the [GitHub Releases page](https://github.com/Md-Saim/Grabbery---Social-Media-videos-downloader/releases/latest) or click [Grabbery-v1.0.0-release.apk](https://github.com/Md-Saim/Grabbery---Social-Media-videos-downloader/releases/latest/download/Grabbery-v1.0.0-release.apk).
2. **Allow Installation**:
   * When prompted by Android, tap **Settings** and toggle **Allow from this source** (or "Install unknown apps").
3. **Install & Launch**:
   * Tap **Install**, then open **Grabbery** from your app launcher.
4. **Grant Permissions**:
   * Grant storage/media permissions when requested so Grabbery can save downloaded media directly into your device's `Download/Grabbery` folder.

---

## 🔍 SEO & Supported Formats Matrix

| Platform | Supported Media Formats | Max Resolution / Bitrate | Direct Audio (MP3/M4A) |
| :--- | :--- | :--- | :---: |
| **YouTube** | Videos, Shorts, Premieres, Public Playlists | Up to 4K (2160p) | ✅ Yes |
| **Instagram** | Reels, Video Posts, Multi-image Carousels | Full HD (1080p) | ✅ Yes |
| **TikTok** | Standard Videos, Shorts (No Watermark) | Source HD | ✅ Yes |
| **Facebook** | Public Videos, Reels, Watch Clips | HD / SD | ✅ Yes |

---

## 👨‍💻 Developer & Creator

<div align="center">

<a href="https://github.com/Md-Saim">
  <img src="https://github.com/Md-Saim.png" width="100px" style="border-radius: 50%; box-shadow: 0 4px 20px rgba(0, 240, 255, 0.4);" alt="Moiz Ud Din Saim"/>
</a>

### **Moiz Ud Din Saim**
*Lead Architect & Creator*

[![GitHub](https://img.shields.io/badge/GitHub-Md--Saim-181717?style=for-the-badge&logo=github)](https://github.com/Md-Saim)
[![Portfolio / Contact](https://img.shields.io/badge/Profile-Moiz%20Ud%20Din%20Saim-00F0FF?style=for-the-badge&logo=safari)](https://github.com/Md-Saim)

</div>

---

## 🔒 License & Intellectual Property

> **Notice:** Grabbery is a **proprietary, closed-source** application.
> All rights reserved © 2026 **Moiz Ud Din Saim** ([@Md-Saim](https://github.com/Md-Saim)).
> 
> This repository is maintained as the official public distribution, releases, documentation, and asset hub for Grabbery. Reverse engineering, decompilation, unauthorized re-distribution, or commercial resale of the compiled application package without explicit written authorization is prohibited.

---

## ⚖️ Disclaimer

Grabbery is intended for personal media backup, educational purposes, and fair-use archiving of public content. Users are responsible for complying with the terms of service of each content provider and respecting intellectual property laws in their jurisdiction.
