# Matrix Digital Rain 🟢

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5 Canvas](https://img.shields.io/badge/Canvas-HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen.svg)](https://barizssh.github.io/matrix-digital-rain/)

A lightweight, zero-dependency HTML5 Canvas and vanilla JavaScript implementation of the iconic **Matrix Digital Rain** (falling code) visual effect. Featuring cascading Japanese Katakana & alphanumeric characters, glowing lead glyphs, dynamic window resizing, and smooth 30 FPS render physics.

[🌐 **View Live Demo**](https://barizssh.github.io/matrix-digital-rain/)

---

![Matrix Digital Rain Preview](assets/preview.jpg)

---

## ✨ Features

- ⚡ **Zero Dependencies**: Pure HTML5 Canvas & vanilla JavaScript (`0` external libraries or heavy assets).
- 💚 **Authentic Movie Visuals**: Glowing bright white lead characters followed by neon green fading streams.
- 📐 **Fully Responsive**: Dynamically adjusts to window resize events without distortion.
- 🚀 **High Performance**: Optimized canvas animation loop with minimal CPU and memory footprint.
- 🔣 **Rich Character Stream**: Classic half-width Japanese Katakana (`ﾊﾐﾋｰｳｼﾅﾓﾆ...`) and alphanumeric symbols.
- 🎛️ **Easily Customizable**: Simple configuration for font size, drop speed, fade rates, and colors.

---

## 🚀 Quick Start

### 1. Run Directly in Browser
Simply clone the repository and open `index.html`:

```bash
git clone https://github.com/barizssh/matrix-digital-rain.git
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
// Customize character set (Katakana + Alphanumeric)
const chars = 'ﾊﾐﾋｰｳｼﾅﾓﾆｻﾜﾂｵﾘｱﾎﾃｹﾒｴｶｷﾑﾕﾗｾﾈｽﾀﾇﾍ0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ';

// Column density and font size
const fontSize = 16; 

// Glow effect on lead characters
ctx.shadowColor = '#00FF41'; 
ctx.shadowBlur = 8;

// Trail fade rate (lower alpha = longer trails)
ctx.fillStyle = 'rgba(0, 0, 0, 0.05)';
```

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome!
Feel free to open an [issue](https://github.com/barizssh/matrix-digital-rain/issues) or submit a pull request.

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
