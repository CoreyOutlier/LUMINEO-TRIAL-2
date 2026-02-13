# Lumineo.ai Website

Lumineo.ai — Intelligent solutions for a brighter future.

A modern, dark-themed multi-page website inspired by [300feetout.com](https://www.300feetout.com/), built with HTML5, CSS3, vanilla JavaScript, and GSAP animations.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, strategy, marquee, services preview, portfolio, testimonial, contact form |
| Services | `services.html` | AI/tech services, creative services, 4-step process |
| Work | `work.html` | Filterable portfolio with 6 project case studies |
| About | `about.html` | Company story, values, team profiles, stats |

## Features

- **Dark theme** with subtle gradient orbs and grid backgrounds
- **Bold typography** using Space Grotesk (headlines) and Inter (body)
- **GSAP scroll animations** — parallax effects, staggered reveals, background text movement
- **Scrolling marquee** listing capabilities
- **Cursor glow effect** — radial gradient follows mouse movement
- **Animated counters** that count up when scrolled into view
- **SVG abstract graphics** as project card visuals
- **Filterable portfolio** with category tags
- **Contact form** with client-side feedback
- **Fully responsive** — mobile nav, fluid typography, adaptive grids

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, `clamp()`)
- Vanilla JavaScript (Intersection Observer, requestAnimationFrame)
- [GSAP 3.12](https://greensock.com/gsap/) + ScrollTrigger (via CDN)
- [Google Fonts](https://fonts.google.com/) — Space Grotesk, Inter

## Getting Started

Simply open `index.html` in a browser. No build step required.

```bash
# Or use a local server
npx serve .
```

## Project Structure

```
├── index.html          # Home page
├── services.html       # Services page
├── work.html           # Portfolio / work page
├── about.html          # About page
├── css/
│   ├── style.css       # Global styles, components, responsive
│   └── pages.css       # Page-specific styles
├── js/
│   └── main.js         # Animations, navigation, interactivity
└── assets/
    └── favicon.svg     # Site favicon
```
