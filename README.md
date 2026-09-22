# Matrix Digital Rain 🟢

<p align="center">
  <a href="https://barizshah.github.io/matrix-digital-rain/">
    <img src="assets/preview.jpg" alt="Matrix Digital Rain Banner" width="100%">
  </a>
</p>

<p align="center">
  <a href="https://github.com/barizshah/matrix-digital-rain/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/Release-v1.0.0-brightgreen.svg?style=flat-square" alt="Version: v1.0.0"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License: MIT"></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API"><img src="https://img.shields.io/badge/Canvas-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5 Canvas"></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="Vanilla JS"></a>
  <a href="https://barizshah.github.io/matrix-digital-rain/"><img src="https://img.shields.io/badge/Demo-Live_Online-00FF41.svg?style=flat-square" alt="Live Demo"></a>
</p>

<p align="center">
  A lightweight, zero-dependency HTML5 Canvas and vanilla JavaScript recreation of the iconic <strong>Matrix Digital Rain</strong> (falling green code). Designed for cinematic accuracy, distraction-free aesthetics, and seamless performance across all screen sizes.
</p>

<p align="center">
  <a href="https://barizshah.github.io/matrix-digital-rain/"><strong>🌐 Launch Live Web App »</strong></a>
</p>

---

## 📸 Previews

<div align="center">
  <h3>🖥️ Desktop Experience</h3>
  <img src="assets/desktop.png" alt="Matrix Digital Rain Desktop Preview" width="100%">
</div>

<br>

<div align="center">
  <h3>📱 Responsive Mobile Experience</h3>
  <img src="assets/mobile.png" alt="Matrix Digital Rain Mobile Preview" width="340">
</div>

---

## ✨ Highlights & Architecture

- 🟢 **Pure & Distraction-Free**: True-to-source Matrix visual simulation without clutter, advertisements, or heavy third-party bundles.
- ⚡ **Zero Dependencies**: Self-contained in standard HTML5 Canvas & vanilla JavaScript (`0` libraries, `0` external CDNs, single-file architecture).
- 💚 **Authentic Movie Aesthetics**: White-hot lead glyphs cascading into phosphor neon-green trailing tails (`#00FF41`) with organic column depth and genuine 30 FPS film cadence.
- ⛶ **Pixel-Perfect Fullscreen**: Toggle seamlessly with <kbd>F</kbd> or the top header button. Auto-hides UI controls after 3 seconds of inactivity and restores with cursor or touch movement.
- 🧊 **Flawless Pause System**: Freeze rain instantly with <kbd>Space</kbd>. Switch between windowed and fullscreen while paused without canvas clearing, visual gaps, or trail distortion.
- 💤 **Ambient Screensaver (Screen Wake Lock)**: Automatically prevents display sleep when fullscreen mode is engaged, providing a continuous cinematic backdrop. Releases immediately upon exiting fullscreen, pausing, or minimizing.
- ℹ️ **Cyber About Modal**: Accessible via <kbd>I</kbd> or header icon, featuring glassmorphism design, version information, quick shortcuts, and creator attribution.
- 📱 **Adaptive DPI & Safe Area**:
  - Auto-tunes font scaling for desktop (`16px`) and mobile devices (`18px`).
  - Caps Device Pixel Ratio (DPR) at 2 to preserve battery and GPU fill-rate while maintaining crisp rendering on OLED / Retina displays.
  - Honors modern safe-area notches (`viewport-fit=cover`, `env(safe-area-inset-*)`).

---

## ⌨️ Controls & Keyboard Shortcuts

| Control / Shortcut | Action | Description |
| :---: | :---: | :--- |
| <kbd>Space</kbd> | **Pause / Play** | Freezes code streams in place or resumes cascading animation |
| <kbd>F</kbd> | **Fullscreen** | Toggles full-bleed fullscreen immersion mode |
| <kbd>I</kbd> | **Cyber About** | Opens the translucent cyberpunk information modal |
| <kbd>Esc</kbd> | **Close Dialog** | Closes the open modal dialog and returns focus |
| Header **`⛶`** | **Fullscreen Button** | Glassmorphic button to toggle fullscreen mode |
| Header **`ⓘ`** | **Info Button** | Glassmorphic button to view information and attribution |

---

## 🚀 Quick Start

### Option 1: Open Directly
Clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/barizshah/matrix-digital-rain.git
cd matrix-digital-rain

# Open on Linux
xdg-open index.html

# Open on macOS
open index.html

# Open on Windows
start index.html
```

### Option 2: Run via Local HTTP Server
```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (npx)
npx serve
```
Then visit [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🛠️ Configuration & Customization

All visual tuning parameters can be modified directly within `index.html`:

```javascript
// Authentic Katakana, Latin symbols, and matrix numbers
const chars = 'ﾊﾐﾋｰｳｼﾅﾓﾆｻﾜﾂｵﾘｱﾎﾃｹﾒｴｶｷﾑﾕﾗｾﾈｽﾀﾇﾍ0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ:・."=*+-<>¦｜';

// Target 30 FPS for iconic film cadence + thermal/battery efficiency
const TARGET_FPS = 30;

// Trail fade rate (lower alpha = longer persistence, higher = shorter trails)
ctx.fillStyle = 'rgba(0, 0, 0, 0.08)';

// Lead character highlight color
ctx.fillStyle = '#E8FFE8';

// Main stream phosphor green color
ctx.fillStyle = '#00FF41';
```

---

## 👨‍💻 Author

Created and maintained by **Bariz Shah** ([@barizshah](https://github.com/barizshah)).

- GitHub: [@barizshah](https://github.com/barizshah)
- Repository: [matrix-digital-rain](https://github.com/barizshah/matrix-digital-rain)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open an [issue](https://github.com/barizshah/matrix-digital-rain/issues) or submit a pull request.

If you enjoy this project, consider giving it a ⭐ on [GitHub](https://github.com/barizshah/matrix-digital-rain)!

---

## 📄 License

This project is open-source and distributed under the [MIT License](LICENSE).
