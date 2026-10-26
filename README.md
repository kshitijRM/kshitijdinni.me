# ECHO — Editorial Developer & Designer Portfolio

<div align="center">

  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![License](https://img.shields.io/badge/License-MIT-000000?style=for-the-badge)](LICENSE)

  <p align="center">
    <strong>A bespoke, high-performance monochrome editorial portfolio showcasing digital craftsmanship, spatial web animations, and interactive design engineering.</strong>
  </p>

  <p align="center">
    Crafted by <strong><a href="https://github.com/Jishnu09-siuu">Jishnu Mondal</a></strong> — Designer & Full-Stack Creative Developer.
  </p>

</div>

---

## ✦ Overview

**ECHO** is an editorial developer and designer portfolio engineered with a focus on typography, fluid physics, and cutting-edge web graphics. Built around a curated monochrome aesthetic, it marries brutalist minimalism with rich micro-interactions, hardware-accelerated scroll animations, and interactive 3D drum reel navigation.

Whether presenting design systems, full-stack applications, or bespoke brand identities, ECHO provides an immersive editorial reading and browsing experience.

---

## ✦ Key Features & Interactive Architecture

### 1. 🪐 Custom ECHO Orbital Preloader
- Seamless intro experience with an orbital wavy dot animation synchronized via `requestAnimationFrame`.
- Auto-detects first load and dissolves smoothly to unveil the editorial hero section.

### 2. 🗞️ Editorial Hero & Metallic Typography Shaders
- Fluid responsive typography driven by dynamic viewport calculations (`clamp` / `vw`).
- Multi-layer metallic header effects and integrated portrait depth masking.
- Intersection-observer-powered entrance reveals that gracefully retrigger on revisit.

### 3. 🔍 `ScrollExpandMedia` Kinetic Canvas
- Scroll-driven media expansion stage that smoothly interpolates card dimensions, aspect ratio, and blur filters.
- Dual-layer GPU-accelerated unblur rendering running at 120 FPS without reflow penalties.
- Minimalist perimeter content layout ensuring 100% unobscured artwork visibility.

### 4. 🧭 Horizontal Spatial Experience Canvas
- Sticky horizontal timeline translating vertical user scroll into horizontal spatial progression.
- Interactive timeline panels displaying milestones, career history, and "living flow" energy animations.
- Accessible fallback honoring user OS preferences (`prefers-reduced-motion`).

---

## ✦ Tech Stack

| Domain | Technology | Description |
|---|---|---|
| **Structure** | HTML5 / Semantic Web | SEO-optimized, accessible markup with meta hierarchy |
| **Styling** | Vanilla CSS + Tailwind CSS v3 | Custom dark/light design tokens, typography & CSS variables |
| **Logic & Motion** | Vanilla JavaScript (ES Modules) | Lightweight, zero-framework overhead, modular components |
| **Typography** | Plus Jakarta Sans | Editorial modernist sans-serif loaded from Google Fonts |
| **Components** | `scroll-expand-media`, `experience-section` | Bespoke modular UI engines |

---

---

## ✦ Project Structure

```bash
ECHO-WEBSITE/
├── index.html                   # Core single-page portfolio layout & markup
├── scroll-expand-media.js       # Scroll-driven media expansion engine
├── ScrollExpandMedia.tsx        # Component source reference
├── experience-section.js        # Horizontal spatial timeline engine
├── package.json                 # Project configuration & scripts
└── assets/                      # Brand assets, portrait imagery, and icons
```

---

## ✦ Getting Started Locally

This project is built using native ES modules and standard web technologies. You can run it with any local HTTP server:

### Prerequisites
- Python 3.x **or** Node.js installed on your machine.

### Option 1: Python Simple HTTP Server (Recommended)
```bash
# Clone the repository
git clone https://github.com/Jishnu09-siuu/ECHO-WEBSITE.git
cd ECHO-WEBSITE

# Run local development server
npm start
# or directly:
python3 -m http.server 8080
```
Then navigate to `http://localhost:8080` in your browser.

### Option 2: Node.js / Vite / `npx serve`
```bash
npx serve .
# or
npx live-server
```

---

## ✦ Deployment

Because ECHO is completely static and modular, it can be deployed instantly to any edge hosting provider:

- **Vercel**: Run `vercel` from the root directory or connect the GitHub repository.
- **Netlify**: Drag and drop the folder or connect via Git with publish directory set to `/`.
- **GitHub Pages**: Head to repository **Settings > Pages** and set source to branch `main` and folder `/ (root)`.

---

## ✦ Connect & Socials

- **Portfolio**: [Jishnu Mondal](https://jishnumondal.vercel.app/)
- **GitHub**: [@Jishnu09-siuu](https://github.com/Jishnu09-siuu)
---

## ✦ License

This project is open-source and available under the [MIT License](LICENSE).
# kshitijdinni.me
