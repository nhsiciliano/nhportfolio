---
title: El Rincón del Arte · Landing Page
publishDate: 2024-04-15 00:00:00
img: /assets/stock-3.jpg
img_alt: Modern dance academy landing page with pastel gradients and clean layout
description: |
  Marketing site built with Astro 5 to showcase El Rincón del Arte's dance programs, teaching style, and contact paths with a minimalist pastel aesthetic.
tags:
  - Astro
  - Web Design
  - Landing Page
---

# El Rincón del Arte · Landing Page

Web project built with [Astro 5](https://astro.build/) for the dance academy **El Rincón del Arte**, crafted to highlight its artistic proposal, teaching styles, and contact channels through a modern, minimalist aesthetic. The goal is to deliver a smooth first digital touchpoint tailored to prospective students and their families.

## 🧱 Technology Stack

- **Astro 5** as the core framework, focused on Static Site Generation with targeted islands of interactivity.
- **TypeScript** baked in to guarantee typed components and data contracts.
- **Modular CSS** (no framework) organised in `src/styles/global.css`, featuring responsive design, soft animations, and CSS variables for the pastel palette.
- **Deployment on Vercel** via `@astrojs/vercel`, optimising static builds and continuous integration.
- Development tooling: PNPM, Astro Check, Netlify forms compatibility.

## ✨ Key Features

- Sticky navigation with logo, internal anchors, and social links (Instagram and YouTube).
- Hero section with a call to action, informational badges, and a featured photo.
- Alternating cards for dance styles (Classical, Contemporary, Urban, Flex, Training) with bespoke gradients.
- Interactive carousel gallery and lightbox to explore full-size imagery.
- “About Me” section spotlighting the career of Leila Palavecino.
- 2025 schedule grid with day-by-day and level details.
- Contact form ready to integrate with Netlify to capture inquiries.
- Footer with branding, calls to action, and external links.


## 💼 Applied Knowledge

- Led the end-to-end redesign of El Rincón del Arte’s landing page, transforming Astro’s base template into a responsive site with a distinctive identity.
- Implemented reusable modular components (navbar, hero sections, style cards, carousel, form, footer) powered by strongly typed configuration files.
- Applied modern UI principles: soft gradients, transitions, `fade-up` animations, and an accessible carousel with lightbox views.
- Structured the project for readability and scalability through dedicated `components`, `data`, and `styles` directories.
- Readied the application for continuous deployment on Vercel with the official adapter and support for backend-free form submissions.

---

For testing or iterations, start the environment with `pnpm dev` and open `http://localhost:4321`.
