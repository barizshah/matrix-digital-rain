# Matrix Digital Rain 🟢

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Version: v1.0.0](https://img.shields.io/badge/Release-v1.0.0-brightgreen.svg)](https://github.com/barizshah/matrix-digital-rain/releases/tag/v1.0.0)
[![HTML5 Canvas](https://img.shields.io/badge/Canvas-HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen.svg)](https://barizshah.github.io/matrix-digital-rain/)

A lightweight, pure, zero-dependency HTML5 Canvas and vanilla JavaScript implementation of the iconic **Matrix Digital Rain** (falling code) visual effect. Clean, distraction-free, and meticulously optimized for both mobile and desktop screens.

[🌐 **View Live Demo**](https://barizshah.github.io/matrix-digital-rain/)

---

## 🖥️ Desktop Preview

![Matrix Digital Rain Desktop Preview](assets/desktop.png)


---

## 📱 Mobile Preview

<p align="center">
  <img src="assets/mobile.png" alt="Matrix Digital Rain Mobile Preview" width="300">
</p>

---

## ✨ Features in v1.0.0

- 🟢 **Pure & Distraction-Free**: Clean, authentic Matrix visual effect with no bloated menus, clutter, or external dependencies.
- ⚡ **Zero Dependencies**: Pure HTML5 Canvas and vanilla JavaScript (`0` libraries, `0` external assets, self-contained single-file).
- 💚 **Authentic Movie Visuals**: Glowing bright white-hot lead glyphs cascading into phosphor neon-green fading trails (`#00FF41`) with organic column depth and authentic 30 FPS film cadence.
- ⛶ **Flawless Fullscreen**: Quick-toggle button in the header and hotkey <kbd>F</kbd>. Includes auto-fade HUD timer and full-bleed pixel-perfect canvas rendering with zero gap.
- 🧊 **Perfect Pause State**: Freeze rain instantaneously with <kbd>Space</kbd>. Seamlessly transition into and out of fullscreen mode while paused without visual distortion, gaps, or animation resets.
- ℹ️ **Cyber About Modal**: Translucent glassmorphism info dialog featuring keyboard shortcuts, version badge, and creator attribution.
- 📱 **Mobile & Desktop Optimized**:
  - Automatically adapts font size and column density for desktop (`16px`) and mobile (`18px`).
  - Device Pixel Ratio (DPR) capped at 2 to ensure razor-sharp text on Retina/OLED displays while preserving GPU fill-rate and battery life.
  - Safe-area insets support (`viewport-fit=cover`, `env(safe-area-inset-*)`) for notched phone displays.
- 💤 **Screensaver Mode (Screen Wake Lock)**: Activates automatically when entering fullscreen mode to keep your display awake as a cinematic ambient screensaver; releases immediately when exiting fullscreen, paused, or minimized.
- 🔣 **Rich Character Stream**: Authentic half-width Japanese Katakana (`ﾊﾐﾋｰｳｼﾅﾓﾆ...`), Latin letters, numbers, and matrix symbols.

---

## ⌨️ Controls & Shortcuts

| Control / Shortcut | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Pause / Resume animation |
| <kbd>F</kbd> | Toggle Fullscreen mode |
| <kbd>I</kbd> | Toggle Cyber About dialog |
| <kbd>Esc</kbd> | Close Cyber About dialog |
| **Header Button (⛶)** | Toggle Fullscreen mode |
| **Header Button (ⓘ)** | Open Cyber About dialog |

---

## 🚀 Quick Start

### 1. Run Directly in Browser
Clone the repository and open `index.html`:

```bash
git clone https://github.com/barizshah/matrix-digital-rain.git
cd matrix-digital-rain

# Open on Linux
xdg-open index.html

# OR open on macOS
open index.html
```

### 2. Run with a Local Web Server
You can also use Python's built-in HTTP server:

```bash
python3 -m http.server 8000
```
Then open your browser to [http://localhost:8000](http://localhost:8000).

---

## 🛠️ Customization

Animation parameters can be tweaked directly inside `index.html`:

```javascript
// Authentic Katakana, Latin symbols, and numbers
const chars = 'ﾊﾐﾋｰｳｼﾅﾓﾆｻﾜﾂｵﾘｱﾎﾃｹﾒｴｶｷﾑﾕﾗｾﾈｽﾀﾇﾍ0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ:・."=*+-<>¦｜';

// Target 30 FPS for iconic film cadence + thermal/battery efficiency
const TARGET_FPS = 30;

// Trail fade rate (lower alpha = longer trails)
ctx.fillStyle = 'rgba(0, 0, 0, 0.08)';
```

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome!
Feel free to open an [issue](https://github.com/barizshah/matrix-digital-rain/issues) or submit a pull request.

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
