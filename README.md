# 🎬 EDGE PLAYER

A sleek, gesture-driven web video player with cinematic **ambient glow (Ambilight)**, YouTube + direct MP4 support, and a fully custom mobile-friendly UI — built as a single static page, ready to deploy on Netlify.

![Made with HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Netlify Ready](https://img.shields.io/badge/Deploy-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

---

## ✨ Features

- 🌈 **Ambient Glow (Ambilight)** — a soft, blurred glow behind the player synced to the video's live colors
- 📺 **Dual source support** — paste a direct `.mp4` link *or* a YouTube watch URL
- 👆 **Gesture controls** — tap zones for play/pause, double-tap zones to seek ±10s
- 🔒 **Screen lock** — lock the player to prevent accidental taps mid-watch
- 🔍 **Zoom to fill** — toggle between fit and fill (cover) modes
- ⚡ **Playback speed control** — cycle through 0.5x to 2.0x
- 🖥️ **Fullscreen mode** with auto-hiding controls
- 📱 **Responsive** — adapts to portrait and landscape video automatically
- 🔗 **Shareable links** — pass `?url=` in the query string to auto-load a video

---

## 🚀 Quick Start

### Option 1: Deploy to Netlify
1. Fork or clone this repo
2. Drag & drop the folder into [Netlify Drop](https://app.netlify.com/drop), or connect the repo via **Netlify → New site from Git**
3. Done — your player is live 🎉

### Option 2: Run locally
```bash
git clone https://github.com/sai-core/Netlify.git
cd Netlify
# just open index.html in your browser, no build step needed
```

---

## 🎮 Controls

| Action | Gesture / Key |
|---|---|
| Play / Pause | Tap center of video / `Space` |
| Seek −10s | Double-tap left side / `←` |
| Seek +10s | Double-tap right side / `→` |
| Show/hide controls | Single tap |
| Fullscreen | Fullscreen button / `F` |
| Lock screen | Lock icon (top-left) |
| Change speed | Speed badge (bottom-right) |
| Zoom to fill | Zoom icon (bottom-right) |

---

## 🔗 Loading a Video via URL

You can deep-link directly to a video:

```
https://your-site.netlify.app/?url=https://example.com/video.mp4
```

Both direct video URLs and YouTube watch links are supported.

---

## 🛠️ Tech Stack

Pure **HTML + CSS + vanilla JavaScript** — no frameworks, no build tools, no dependencies. Just one `index.html` file.

---

## 📄 License

This project is free to use and modify.
