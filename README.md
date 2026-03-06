# Arif Zakwan — Personal Portfolio

A clean, single-page personal portfolio website for an IT Enthusiast & Automation Specialist based in Malaysia.

## Overview

This is a fully self-contained `index.html` portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks or build tools required. It showcases skills, projects, and contact information with a polished editorial aesthetic.

## Features

- **Custom animated cursor** — dot + trailing ring that reacts to hoverable elements
- **Sticky navigation** — transparent on load, frosted-glass blur on scroll with active section highlighting
- **Responsive mobile menu** — full-screen overlay with animated hamburger toggle
- **Scroll reveal animations** — elements fade up into view as you scroll
- **Hero section** — name, bio, CTA buttons, and highlight stat cards
- **About section** — tagline, bio paragraphs, and a 2×2 facts grid
- **Skills grid** — 6 skill cards with SVG icons, descriptions, and category tags
- **Projects grid** — cards for featured projects with tags and GitHub links
- **Contact section** — social/email links + a contact form with `mailto:` fallback
- **Noise texture overlay** — subtle grain effect for depth

## Tech Stack

- **HTML5 / CSS3 / Vanilla JS** — zero dependencies
- **Google Fonts** — DM Serif Display & DM Sans
- **IntersectionObserver API** — for scroll-based animations and active nav tracking
- **CSS custom properties** — for consistent theming (paper, ink, accent colours)

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | About | Background, tagline, and key facts |
| 02 | Skills & Stack | Python, SQL, AI/ML, CRM, Marketing Automation, Next.js |
| 03 | Projects | n8n Automations, Dabox Chatbot AI |
| 04 | Contact | GitHub, LinkedIn, Email, and contact form |

## Usage

Just open `index.html` in any browser — no server or build step needed.

```bash
open index.html
```

## Customisation

All colours are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --ink: #0f0f0f;
  --paper: #f5f2ec;
  --accent: #c8602a;
  /* ... */
}
```

## Contact

- **Email:** arifzakwan2001@gmail.com
- **LinkedIn:** linkedin.com/in/arif-zakwan
- **GitHub:** github.com/ArfZkwn-coder
