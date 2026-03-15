# CodeAlpha_music-player
Frontend Development Intenship Task - CodeAlpha
# ?? Music Player — CodeAlpha Internship Task 4

> **Intern:** Harishanker S.T
> **Student ID:** CA/DF1/32160
> **Domain:** Frontend Development
> **Duration:** 10th March 2026 – 10th April 2026
> **Organization:** [CodeAlpha](https://www.codealpha.tech)

---

## ?? Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Screenshots](#screenshots)
- [Connect](#connect)

---

## About

A stylish, retro-inspired **Music Player** built with pure HTML, CSS, and JavaScript as part of the **CodeAlpha Frontend Development Internship**. It features a spinning vinyl record animation, a live playlist, progress bar with seek, volume control, and autoplay/shuffle modes — all in a single self-contained HTML file with zero dependencies.

---

## Features

| Feature | Description |
|---------|-------------|
| ??? Play / Pause / Prev / Next | Full playback controls |
| ?? Vinyl Record Animation | Spins while playing, pauses when stopped |
| ??? Album Art | Displayed in vinyl center, changes per track |
| ?? Dynamic Background | Radial gradient shifts color per track |
| ?? Progress Bar | Click anywhere on the bar to seek |
| ?? Timestamps | Live current time & total duration display |
| ?? Volume Slider | Smooth volume control with % readout |
| ?? Autoplay Toggle | Auto-advances to the next track on end |
| ?? Shuffle Toggle | Picks a random next track |
| ?? Playlist Panel | Lists all tracks with animated sound bars on active |
| ?? Keyboard Shortcuts | Space, Arrow Left, Arrow Right |
| ?? Responsive Design | Works on mobile, tablet, and desktop |

---

## Tech Stack

```
HTML5        — Semantic structure & Audio API
CSS3         — Custom properties, Flexbox, Keyframe animations
JavaScript   — Vanilla ES6+, DOM manipulation, HTMLAudioElement API
Google Fonts — Space Mono + Syne
Unsplash     — Sample album art (via URL)
SoundHelix   — Royalty-free audio samples (via URL)
```

> No frameworks. No npm. No build step. Just open and run.

---

## How to Run

### Option 1 — Open directly in browser

```bash
# Clone the repository
git clone https://github.com/your-username/CodeAlpha_MusicPlayer.git

# Open the file in your browser
cd CodeAlpha_MusicPlayer
open music-player.html
```

### Option 2 — VS Code Live Server

1. Install the **Live Server** extension in VS Code
2. Right-click `music-player.html` ? **"Open with Live Server"**

> ?? An internet connection is needed to stream the sample audio from SoundHelix.
> To use local tracks, replace the `src` values in the `tracks` array with paths to your own `.mp3` files:
> ```javascript
> src: './audio/your-song.mp3'
> ```

---

## Project Structure

```
CodeAlpha_MusicPlayer/
?
??? music-player.html     # All HTML + CSS + JS in one file
```

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `?` Arrow Right | Next track |
| `?` Arrow Left | Previous track (or restart if > 3s played) |

---

## Screenshots

> _Add your screenshots here after running the project locally._

```markdown
![Music Player Preview](screenshots/player.png)
```

---

## Connect

**Harishanker S.T**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/your-username)

---

> ?? **CodeAlpha** · [www.codealpha.tech](https://www.codealpha.tech) · services@codealpha.tech