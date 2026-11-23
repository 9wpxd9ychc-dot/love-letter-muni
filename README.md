# LOVE LETTER — Muni

A mobile-first romantic greeting card with a real-time Three.js 3D envelope and an animated letter reveal.

## Features

- Interactive 3D envelope rendered with Three.js.
- Animated opening and closing, with a CSS fallback if WebGL or the Three.js CDN is unavailable.
- Personal Russian-language letter for Muni.
- Responsive layout for phones, tablets and desktop.
- Keyboard support (Escape closes the letter), visible focus, and reduced-motion support.
- No backend, account, or paid API required.

## Run locally

Serve this folder with any static HTTP server, for example:

```bash
python -m http.server 8080
```

Then open http://localhost:8080.

Three.js and the display fonts are loaded from public CDNs. If Three.js cannot load, the page keeps the letter interaction available with a lightweight visual fallback.
