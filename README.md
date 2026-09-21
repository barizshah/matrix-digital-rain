# Matrix Digital Rain 🟢

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Version: v1.0.1](https://img.shields.io/badge/Release-v1.0.1-brightgreen.svg)](https://github.com/barizshah/matrix-digital-rain/releases/tag/v1.0.1)
[![HTML5 Canvas](https://img.shields.io/badge/Canvas-HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen.svg)](https://barizshah.github.io/matrix-digital-rain/)

A lightweight, high-performance, zero-dependency HTML5 Canvas and vanilla JavaScript implementation of the iconic **Matrix Digital Rain** (falling code) visual effect. Featuring multi-layer 3D depth parallax, mobile & desktop adaptive frame rates, touch & pointer interactive shockwaves, cyberpunk theme switcher, interactive controls HUD, real-time FPS counter, synthesized Web Audio, and keyboard shortcuts.

[🌐 **View Live Demo**](https://barizshah.github.io/matrix-digital-rain/)

---

![Matrix Digital Rain Preview](assets/preview.jpg)

---

## ✨ What's New in v1.0.1

- 🌌 **3D Depth & Parallax Layering**: Tri-layer streams (Foreground, Midground, Background) with dynamic scaling, varied velocities, and layered luminescence for authentic cinematic depth.
- 📱 **Mobile & Desktop Adaptive Optimization**:
  - Automatically switches between fluid 60 FPS on desktop displays and battery-conserving 30 FPS on mobile devices.
  - Adaptive column stride and background density to minimize GPU fill-rate and thermal throttling on smartphones.
  - Full support for mobile safe areas (`env(safe-area-inset-*)`), iOS status bar translucency, notch ergonomics, and multi-touch swipe/tap gestures.
- 🎨 **Multi-Color Theme Engine**:
  - 🟢 **Matrix Classic** (Iconic Emerald Green)
  - 🔵 **Resurrection Cyan** (The Matrix Resurrections Neon Teal)
  - 🟡 **Cyberpunk Amber** (Retro Terminal Gold)
  - 🔴 **Sith Crimson** (Deep Neon Red)
  - 🟣 **Neon Purple** (Ghost in the Shell / Synthwave Violet)
- 🎛️ **Interactive Cyberpunk HUD**: Sleek, glassmorphic settings panel with real-time sliders for Speed, 3D Parallax toggle, Trail persistence, and live FPS monitor.
- 🔊 **Zero-Asset Audio Synthesis**: Built-in ambient digital hum and data blips synthesized purely with the browser's native Web Audio API (0 KB added download size).
- 💥 **Interactive Shockwaves & Ripples**: Clicking, tapping, or dragging sends ripples through the digital matrix, scattering character streams.
- 📸 **One-Click Snapshots**: Save high-resolution PNG captures of the digital rain instantly.
- ⌨️ **Keyboard Hotkeys**: Full hands-on control via hotkeys.

---

## 📱 Mobile & Touch Experience

- **Touch & Drag**: Tap or drag anywhere on the screen to trigger ripples and scatter cascading glyphs.
- **Responsive Settings HUD**: Tap `⚙️` to adjust rain speed, toggle 3D parallax, change themes, or mute/unmute synthesized digital audio.
- **Outside Tap Dismiss**: Tapping anywhere on the canvas automatically closes the settings HUD on mobile devices.
- **Battery & Thermal Conservation**: The animation automatically pauses when the browser tab is hidden or minimized.

---

## ⌨️ Keyboard Controls & Shortcuts

| Key | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Pause / Resume animation |
| <kbd>H</kbd> | Toggle Settings HUD |
| <kbd>F</kbd> | Toggle Fullscreen |
| <kbd>C</kbd> | Cycle Color Themes |
| <kbd>R</kbd> | Trigger Lightning Flash & Reset |
| <kbd>Esc</kbd> | Close Settings HUD |

---

## 🚀 Quick Start

### 1. Run Directly in Browser
Simply clone the repository and open `index.html`:

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

## 🛠️ Customization & Architecture

The entire project remains **100% dependency-free** and self-contained within `index.html`. Custom settings, character sets, and themes can be customized in JavaScript:

```javascript
// Authentic Katakana, Latin glyphs, and operators
const CHARS = 'ﾊﾐﾋｰｳｼﾅﾓﾆｻﾜﾂｵﾘｱﾎﾃｹﾒｴｶｷﾑﾕﾗｾﾈｽﾀﾇﾍ0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ:・."=*+-<>¦｜';

// Custom theme palette definition
const THEMES = {
  classic: {
    name: 'Matrix Classic',
    lead: '#E8FFE8',
    trail: '#00FF41',
    dim: '#00661a',
    glow: '#00FF41'
  },
  // Add your own custom color themes here!
};
```

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome!
Feel free to open an [issue](https://github.com/barizshah/matrix-digital-rain/issues) or submit a pull request.

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
