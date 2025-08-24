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

## 📸 Preview

<p align="center">
  <img src="assets/screenshot-tray.png" alt="Tray Player Screenshot" width="500"/>
</p>

<p align="center">
  <img src="assets/demo.gif" alt="Mini Player Demo" width="600"/>
</p>

*(Screenshots are placeholders — replace with actual images from your build!)*  

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
```

The compiled binary will be in `target/release/`.

### Run
```bash
./target/release/ytmusicrs
```

The player will appear in your **Windows tray**. Right-click for options, search, and playback controls.

---

## 🛠 Roadmap
- [ ] Cross-platform support (Linux, macOS)  
- [ ] Global hotkeys for playback  
- [ ] Lyrics integration  
- [ ] Theming (dark/light tray icons)  
- [ ] Save favorite playlists  

---

## 🤝 Contributing
Contributions are welcome!  
If you'd like to fix bugs, add features, or improve documentation:  

1. Fork the repo  
2. Create a new branch (`git checkout -b feature/amazing-feature`)  
3. Commit your changes (`git commit -m 'Add amazing feature'`)  
4. Push to the branch (`git push origin feature/amazing-feature`)  
5. Open a Pull Request  

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## ⚠️ Disclaimer
This project is **not affiliated with or endorsed by YouTube or Google**.  
It uses public YouTube streaming via `yt-dlp` for educational and personal use only.
