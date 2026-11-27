# Edge AI Inference — Animated Landing Page

A landing page concept for an edge AI inference product, built to practice scroll-driven animation. It has a 3D globe, an animated circuit graphic, and smooth scrolling.

> This is a design and animation study. It is not affiliated with Gcore or any other company.

## Features

- **Scroll-triggered animations** with GSAP and ScrollTrigger.
- **3D globe** made with Three.js.
- **Animated circuit lines** drawn on canvas.
- **Smooth scrolling** with Lenis.
- Responsive layout with Lucide icons.

## Tech stack

Vite, GSAP, Three.js, Lenis, Lucide, plain JavaScript and CSS.

## Getting started

```bash
npm install
npm run dev       # start the dev server
npm run build     # build to dist/
npm run preview   # preview the build
```

## Project structure

```
index.html        Page markup and sections
src/
  main.js         GSAP timelines, ScrollTrigger, and Lenis setup
  globe.js        Three.js globe
  circuit.js      Circuit-line animation
  style.css       Styles
```
