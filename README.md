# PORTFOLIA

A modern, fully responsive **personal portfolio website** for Lucky — Full Stack Developer & Creative Problem Solver.

🔗 **Live Repo:** https://github.com/Luckysaini01/PORTFOLIA

---

## 📁 Project Structure

```
PORTFOLIA/
├── indexport.html      # The complete portfolio (single-file app)
└── lucky_centered.png  # Hero photo — centered, enhanced portrait
```

Everything lives in **one HTML file** — HTML, CSS, and JavaScript are all inline, so there is no build step, no dependencies, and no framework to install. Just open `indexport.html` in a browser and it works.

---

## ✨ Features

- **Single-file architecture** — zero build tools, zero npm installs. Pure HTML + CSS + JS.
- **Fully responsive** — desktop grid layout collapses to a single-column mobile layout at `768px`, with a hamburger menu for navigation.
- **Hero section** — large name, role title, CTA buttons ("Get In Touch", "View Work") and a framed portrait photo (`lucky_centered.png`, scaled with `object-fit: cover` so it crops cleanly at every screen size).
- **About section** — bio + animated stat cards (Years Experience, Projects Done, Happy Clients, Tech Stacks).
- **Skills section** — categorized skill tags: Frontend (HTML5, CSS3, JavaScript, React, Tailwind, TypeScript), Backend (Python, Node.js...), and more.
- **Projects section** — project cards with descriptions and GitHub links.
- **Contact section** — email button, plus social links to GitHub, LinkedIn, X (Twitter), and Instagram.
- **Smooth scrolling** — `scroll-behavior: smooth` for anchor navigation.
- **Reveal animations** — sections fade/slide in as you scroll.
- **Subtle grain overlay** — an SVG noise texture overlay for a premium dark aesthetic.

---

## 🎨 Design

| Detail | Value |
|---|---|
| Theme | Dark (`#0a0a0f` background) |
| Accent colors | Gold `#d4a843`, Purple `#6c63ff` |
| Headings font | Playfair Display (serif) |
| Body font | DM Sans (300 weight) |
| Cards/Surfaces | `#12121a` / `#1a1a26` with `#2a2a3e` borders |

---

## 🖼️ The Photo (`lucky_centered.png`)

The hero portrait was post-processed for best presentation:

- **Cropped & centered** — trimmed to the subject with even margins (verified symmetric: 78px left/right, 57px top/bottom on a 512×512 canvas)
- **Enhanced** — brightness +8%, contrast +12%, saturation +20%
- **Resized** — 1024×1024 → 512×512 with Lanczos resampling and transparent background preserved

---

## 🚀 Getting Started

### Run locally
```bash
git clone https://github.com/Luckysaini01/PORTFOLIA.git
cd PORTFOLIA
# just open indexport.html in any browser
```

### Deploy to GitHub Pages
1. Repo **Settings → Pages**
2. Source: **Deploy from a branch** → `main` → `/ (root)`
3. Site goes live at `https://luckysaini01.github.io/PORTFOLIA/`

---

## 🛠️ Tech Used

- **HTML5** — semantic section structure
- **CSS3** — CSS Grid + Flexbox, custom properties (variables), media queries, keyframe animations
- **Vanilla JavaScript** — mobile nav toggle, scroll-reveal animations
- **Google Fonts** — Playfair Display + DM Sans

---

## 📬 Contact

- **Email:** luckysaini09860986@gmail.com
- **GitHub:** [Luckysaini01](https://github.com/Luckysaini01)
- **LinkedIn:** [lucky-saini](https://www.linkedin.com/in/lucky-saini-ba1b99407/)

---

© 2026 Lucky. All rights reserved.
