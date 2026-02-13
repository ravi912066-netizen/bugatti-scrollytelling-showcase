# 🏎️ Bugatti Chiron — Scrollytelling Showcase

An ultra-premium, single-page scrollytelling experience for the Bugatti Chiron. Scroll-controlled image sequence, HUD-style overlays, and cinematic transitions — all in one static `index.html`.

![Hero](https://img.shields.io/badge/BUGATTI-CHIRON-00d4ff?style=for-the-badge&labelColor=000)
![HTML](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Glassmorphism-1572B6?style=flat-square&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/Vanilla_JS-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## ✨ Features

- **Scroll-Controlled Canvas** — 114-frame image sequence rendered on `<canvas>` with `requestAnimationFrame`
- **HUD Scroll Phases** — Three cinematic phases (Hero → Design → Engine) driven purely by scroll position
- **Glassmorphism Navbar** — Frosted-glass effect with magnetic hover CTA
- **Retina Support** — `devicePixelRatio`-aware canvas for crisp 4K rendering
- **Specs & Features Sections** — Fade-in cards with hover glow effects via `IntersectionObserver`
- **Film Grain Overlay** — Subtle SVG noise texture for cinematic feel
- **Zero Dependencies** — No frameworks, no build tools, no bundlers

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 Semantic |
| Rendering | Canvas 2D API |
| Styling | Vanilla CSS (custom properties, glassmorphism) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Orbitron + Rajdhani |

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/ravi912066-netizen/bugatti-scrollytelling-showcase.git
cd bugatti-scrollytelling-showcase

# Serve locally
python3 -m http.server 8080
# Open http://localhost:8080
```

Or just open `index.html` directly in your browser.

## 📁 Project Structure

```
├── index.html                    # Everything — HTML, CSS, JS
└── images/
    └── bugatti-sequence/
        ├── frame-001.jpg         # First frame
        ├── frame-002.jpg
        ├── ...
        └── frame-114.jpg         # Last frame
```

## 🎨 Design System

| Token | Value |
|-------|-------|
| Background | `#050508` |
| Accent | `#00d4ff` (Electric Blue) |
| Silver | `#c0c0c0` |
| Heading Font | Orbitron |
| Body Font | Rajdhani |
| Aesthetic | Sci-Fi HUD |

## 📦 Deploy

Static-deploy ready. Upload the entire folder to any static host:

- **GitHub Pages** — Settings → Pages → Deploy from branch
- **Netlify / Vercel** — Drag & drop the folder
- **Any web server** — Just serve the directory

## 📄 License

This is a design concept showcase. Bugatti® is a registered trademark of Bugatti Automobiles S.A.S.
