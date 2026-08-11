# BeatRender — Releases

**BeatRender** is a Windows desktop app for type-beat producers: import your producer library, pair covers, render MP4 videos, and ship beats to **YouTube** and **BeatStars** — from one place.

This repo is the **release channel only**: it hosts the installers and release notes. **The BeatRender source code is private** and not published here.

---

## 📥 Download the latest version

Go to **[Releases](https://github.com/prodbymosca/BeatRender-Releases/releases/latest)** and download `BeatRender_<version>_x64-setup.exe` (or the `.msi`).

> The app also updates itself: on launch it checks this page for a newer version and installs it automatically. You can force a check anytime in **Settings → Check for updates**.

## 🖥 System requirements

- Windows 10 or 11 (64-bit)
- FFmpeg is bundled and set up automatically on first run (SHA-256 verified).

## ✨ What BeatRender does

| Area | What you get |
|---|---|
| **Smart Import** | Scans producer libraries, groups complete packs (MP3 + master WAV + stems + FLP), "Only new" rescan |
| **Library** | Beats + covers, pairing, upload tracking, auto-hide for uploaded beats |
| **Render** | Type-beat MP4 videos from any beat + cover (waveform, size presets, backgrounds) |
| **YouTube** | Waitlist, scheduling, privacy, SEO tags, description templates, resumable upload |
| **BeatStars** | Track pack uploads (audio + stems + artwork), link injected into the YouTube description |
| **Cover Studio** | Pinterest "For you", advanced edit (48 looks, transform, adjust, FX, watermark), presets |
| **Themes** | DAW palettes (FL Studio / Ableton / Cubase), custom themes, animated backgrounds |

## 🔄 How updates work

1. On launch, BeatRender checks `https://api.github.com/prodbymosca/BeatRender-Releases/releases/latest`.
2. If a newer version exists, it downloads the installer (SHA-256 verified against the release), runs it silently, and restarts.
3. The check is public and unauthenticated — no login needed to get updates.

## 📄 Version history

| Version | Highlights |
|---|---|
| **v1.0.0** | First production release — Smart Import, Render, YouTube waitlist/upload/schedule, BeatStars track packs, Cover Studio, themes, licensing, automatic updates |

---

**Support:** for license/account issues, contact the seller. For app issues, check **Info → Quick fixes** inside the app first.
