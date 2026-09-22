# Matrix Digital Rain 🟢

[![Release: v1.0.0](https://img.shields.io/badge/Release-v1.0.0-brightgreen.svg)](https://github.com/barizshah/matrix-digital-rain/releases/tag/v1.0.0)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Demo-Online-00FF41.svg)](https://barizshah.github.io/matrix-digital-rain/)

A lightweight, distraction-free HTML5 Canvas & vanilla JavaScript recreation of the iconic Matrix digital rain visual effect. Meticulously optimized for smooth rendering across desktop and mobile screens.

[🌐 **Launch Live Demo**](https://barizshah.github.io/matrix-digital-rain/)

---

## 🖥️ Preview

![Matrix Digital Rain Preview](assets/desktop.png)

<p align="center">
  <img src="assets/mobile.png" alt="Matrix Digital Rain Mobile Preview" width="300">
</p>

---

## ✨ Features

- **Authentic Visuals**: Bright white-hot lead glyphs cascading into phosphor neon-green trails with 30 FPS film cadence.
- **Zero Dependencies**: Pure HTML5 Canvas and vanilla JavaScript in a single self-contained file.
- **Flawless Fullscreen & Pause**: Instant freeze/resume with <kbd>Space</kbd> and fullscreen toggle with <kbd>F</kbd> without dropped trails, visual jumps, or gaps.
- **Ambient Screensaver**: Uses the Screen Wake Lock API in fullscreen mode to prevent display sleep.
- **Cyber About Modal**: Translucent glassmorphism info dialog with shortcuts and attribution (<kbd>I</kbd>).
- **Responsive & Battery-Conscious**: Capped DPR rendering, safe-area inset support, and auto-pausing when the tab is hidden.

---

## ⌨️ Controls

| Key / Control | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Pause / Resume animation |
| <kbd>F</kbd> | Toggle Fullscreen |
| <kbd>I</kbd> | Toggle About dialog |
| <kbd>Esc</kbd> | Close dialog |
| **`⛶` Button** | Fullscreen |
| **`ⓘ` Button** | About dialog |

---

## 🚀 Quick Start

Clone the repo and open `index.html` directly in your browser:

```bash
git clone https://github.com/barizshah/matrix-digital-rain.git
cd matrix-digital-rain
xdg-open index.html   # Linux (or use 'open' on macOS / 'start' on Windows)
```

Or serve locally:

```bash
python3 -m http.server 8000
```

---

## 🛠️ Customization

Parameters can be adjusted directly at the top of the `<script>` tag in `index.html`:

```javascript
// Target 30 FPS film cadence
const TARGET_FPS = 30;

// Trail persistence (lower = longer trails)
ctx.fillStyle = 'rgba(0, 0, 0, 0.08)';
```

---

## 📄 License

MIT © [Bariz Shah](https://github.com/barizshah). See [LICENSE](LICENSE) for details.
