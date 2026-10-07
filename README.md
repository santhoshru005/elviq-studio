# Eleviq – Elevate with Intelligence

A static single-page portfolio site for Eleviq, a digital & AI solutions studio. Built with plain HTML5, CSS3, and vanilla JavaScript (no build step).

## Structure

```
portfolio-source/portfolio/
├── index.html      # main page (inline JS: loader, cursor, nav, GSAP animations, slider)
├── portfolio.html  # duplicate of index.html (kept as-is)
├── portfolio.css   # styles
├── favicon.ico
└── assets/         # project screenshots and logos
```

## Run locally

Open `portfolio-source/portfolio/index.html` in a browser — no server or dependencies required.

External CDN dependencies: Google Fonts (Inter, Instrument Serif) and GSAP 3.12.5 + ScrollTrigger (cdnjs).

## Deploy

Deployable as-is to any static host (GitHub Pages, Netlify, Vercel). For GitHub Pages, set the source path to `portfolio-source/portfolio`.
