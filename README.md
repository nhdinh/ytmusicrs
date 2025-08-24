# 🎶 YouTube Music Player (Rust)

A lightweight **YouTube Music player** built with Rust.  
Easily search, browse, and play your favorite YouTube songs — directly from your **Windows traybar**.  
No browser tabs, no distracting video — just the music.  

---

## ✨ Features
- 🔍 **Search YouTube** for songs, albums, or artists  
- 🎵 **Audio-only playback** (no video stream, optimized for music)  
- 📌 **Windows tray integration** — control playback without opening a window  
- ▶️ Basic controls: Play / Pause / Next / Previous  
- 📃 Playlist support (queue multiple songs)  
- 🔊 Adjustable volume, mute/unmute  
- ⚡ Lightweight, minimal resource usage (thanks to Rust)  

---

## 🚀 Getting Started

### Prerequisites
- Windows 10/11  
- [Rust toolchain](https://www.rust-lang.org/tools/install) (latest stable)  
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) installed and in your PATH (for YouTube streaming)  
- [mpv](https://mpv.io/) or other supported audio backend (for playback)  

### Clone & Build
```bash
git clone https://github.com/nhdinh/ytmusicrs.git
cd ytmusicrs
cargo build --release
