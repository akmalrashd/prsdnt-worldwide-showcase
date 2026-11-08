<p align="center"><img src="docs/cover.png" alt="PRSDNT Worldwide cover" width="100%"></p>

# PRSDNT Worldwide: Agency Website

> **Portfolio showcase.** Company profile site for PRSDNT WORLDWIDE, my freelance creative and esports brand. Source is private.

**Live:** prsdntworldwide.com · **Role:** Designer and developer · **Period:** July – October 2026

![React 19](https://img.shields.io/badge/React_19-61DAFB?logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white) ![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?logo=tailwindcss&logoColor=white) ![GSAP](https://img.shields.io/badge/GSAP-88CE02?logo=greensock&logoColor=black)

---

## What it is

A single-page, motion-rich company profile for a multidisciplinary agency (creative media, game top-ups, esports and events, lifestyle apparel). The goal was a bold look that still loads fast, ranks in search and respects accessibility settings.

## Screenshots

<p align="center"><img src="docs/screenshots/desktop-hero.png" width="90%" alt="Hero"></p>
<p align="center">
  <img src="docs/screenshots/desktop-1.png" width="44%" alt="Vision section">
  <img src="docs/screenshots/desktop-2.png" width="44%" alt="Expertise section">
  <img src="docs/screenshots/mobile-hero.png" width="10%" alt="Mobile">
</p>

## System design

### Build and prerender pipeline
![Build and prerender pipeline](docs/diagrams/build-pipeline.png)

### Page and component structure
![Page and component structure](docs/diagrams/component-structure.png)

## Engineering highlights

- **Prerendered React:** a 4-step build (typecheck → client bundle → server bundle → prerender) injects real HTML into `index.html`, so crawlers and slow phones see content without waiting for JavaScript.
- **Motion with care:** one GSAP instance with ScrollTrigger; animations switch off for `prefers-reduced-motion`, and the custom cursor only appears on mouse devices.
- **Contrast rules in the design system:** brand red is measured against the background; the darker red is used only for large text and decoration, and a lighter red is used for normal text to pass WCAG AA.
- `robots.txt`, `sitemap.xml` and an Open Graph image for sharing.

## How I used AI tools

AI coding assistants helped with boilerplate, build scripts and debugging. The brand, layout, motion choices and content are mine.

## Contact

**Muhammad Akmal bin Mohd Rashid**: Software Engineering student, UMPSA.  
Open to a 6-month internship (22 February to 7 August 2027).  
📧 work.akmalrashd@gmail.com · 💼 [linkedin.com/in/akmalrashd](https://www.linkedin.com/in/akmalrashd)
