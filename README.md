# 🎵 Pulse — Music Player

A sleek, modern music player built with pure HTML, CSS, and JavaScript. Pulse features a stunning glassmorphism UI, animated vinyl disc, waveform visualizer, and a fully functional playlist — no frameworks, no dependencies.

---

## ✨ Features

- **Animated Vinyl Disc** — Spins while a track is playing, pauses when stopped
- **Dynamic Theming** — Background gradients, glow effects, and accent colors shift per track
- **Waveform Visualizer** — Animated bar visualizer synced to play/pause state
- **Playlist with Search** — Filter tracks by title, artist, or genre in real time
- **Playback Controls** — Play/Pause, Previous, Next, Shuffle, and Repeat
- **Progress Bar** — Click anywhere on the bar to seek
- **Volume Control** — Slider with live percentage display
- **Autoplay & Shuffle Toggles** — Persistent toggle switches in the player UI
- **Keyboard Shortcuts** — Control playback without touching the mouse
- **Glassmorphism Design** — Frosted glass cards with blur, gradients, and animated orbs
- **Fully Responsive** — Adapts to mobile and desktop layouts

---

## ⌨️ Keyboard Shortcuts

| Key          | Action            |
|--------------|-------------------|
| `Space`      | Play / Pause       |
| `→` Arrow    | Next Track         |
| `←` Arrow    | Previous Track     |
| `↑` Arrow    | Volume Up (+5%)    |
| `↓` Arrow    | Volume Down (-5%)  |

---

## 🚀 Getting Started

No build tools or installation required.

1. **Clone or download** this repository
2. Open `index.html` in any modern browser
3. Hit play and enjoy!

```bash
git clone https://github.com/your-username/pulse-music-player.git
cd pulse-music-player
open index.html
```

---

## 📁 Project Structure

```
pulse-music-player/
│
├── index.html       # All-in-one HTML, CSS & JS
└── README.md        # Project documentation
```

> The entire app lives in a single `index.html` file — styles and scripts are fully inline for zero-dependency portability.

---

## 🎨 Tech Stack

| Technology     | Usage                        |
|----------------|------------------------------|
| HTML5          | Structure & Audio API        |
| CSS3           | Animations, Glassmorphism    |
| Vanilla JS     | Playback logic, DOM control  |
| Google Fonts   | Inter & Outfit typefaces     |
| Unsplash       | Placeholder album artwork    |
| SoundHelix     | Demo audio tracks            |

---

## 🎧 Default Tracks

| # | Title             | Genre     |
|---|-------------------|-----------|
| 1 | Electronic Sunrise | Electronic |
| 2 | Acoustic Dreams    | Acoustic   |
| 3 | Night Drive        | Ambient    |
| 4 | City Pulse         | Synthwave  |
| 5 | Orbital Drift      | Space      |
| 6 | Neon Boulevard     | Synthwave  |
| 7 | Emerald Coast      | Chill      |

To add your own tracks, edit the `tracks` array in the `<script>` section of `index.html`:

```js
{
  title: 'Your Song Title',
  artist: 'Artist Name',
  genre: 'Genre',
  art: 'https://link-to-album-art.jpg',
  color: ['#hexcolor1', '#hexcolor2'],
  src: 'path/to/your-audio.mp3',
  duration: '3:30'
}
```

---

## 📱 Browser Support

Works on all modern browsers that support the HTML5 `<audio>` element and CSS `backdrop-filter`.

| Browser        | Support |
|----------------|---------|
| Chrome 76+     | ✅      |
| Firefox 103+   | ✅      |
| Safari 14+     | ✅      |
| Edge 79+       | ✅      |

---

## 🙋‍♂️ Author

**Harishanker S T**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/harishanker-s-t-938772365)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ and good taste in music.
