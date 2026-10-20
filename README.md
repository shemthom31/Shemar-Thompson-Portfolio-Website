# Shemar Thompson — Portfolio Website

Personal portfolio website for Shemar Thompson, Full-Stack Software Engineer based in London, UK.

**Live at:** [sscourierja.com](https://sscourierja.com) &nbsp;·&nbsp; [github.com/shemthom31](https://github.com/shemthom31) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/shemar-thompson-791842189)

---

## Overview

A single-file, zero-dependency portfolio built with vanilla HTML, CSS, and JavaScript. No build step, no frameworks, no installs — open `index.html` in any browser and it works.

---

## Features

- **Animated hero section** with floating gradient orbs, a subtle grid background, and a typing animation cycling through roles/locations
- **Scroll progress bar** at the top of the page
- **Sticky frosted-glass navbar** that activates on scroll, with a mobile hamburger menu
- **Scroll-triggered fade-in animations** on all sections using IntersectionObserver
- **Project modal popups** — click any project card to open a detailed overlay with description, stack tags, live link, and GitHub repo link. Close with ESC, backdrop click, or the × button
- **Fully responsive** — mobile, tablet, and desktop layouts
- **No dependencies** — Google Fonts is the only external resource (loaded via CDN)

---

## Sections

| Section | Description |
|---|---|
| Hero | Name, animated subtitle, CTAs, social links |
| About | Bio, background story, 4 key stats |
| Skills | 5 categorised skill cards (Languages, Frontend/Mobile, Backend/Data, Cloud/DevOps, AI Tools) |
| Experience | SSCourier — Founder & Technical Lead (2023–Present) |
| Projects | 7 live projects with modal popups, live links, and repo links |
| Education | MSc Software Engineering (Westminster) + BSc Sports Medicine (Howard) with module list |
| Contact | Email, GitHub, LinkedIn, and SSCourier links |

---

## Projects Featured

| Project | Stack | Links |
|---|---|---|
| SSCourier | Next.js, TypeScript, Node.js, Supabase, PostgreSQL, Python | [Live](https://sscourierja.com) |
| Babyja876 | React 19, TypeScript, React Router, Tailwind | [Live](https://babyja876.netlify.app/) · [Code](https://github.com/shemthom31/Babyja876) |
| Todo: Final Quest | React 19, TypeScript, Vite, PWA, Tailwind | [Live](https://www.todofinalquest.netlify.app) · [Code](https://github.com/shemthom31/Todo-Final-Quest) |
| A5 Notebooks | React 19, TypeScript, Motion | [Live](https://a5notebook.netlify.app/) · [Code](https://github.com/shemthom31/a5Notebook) |
| Jamaica Pay | TypeScript, React | [Live](https://jamaicapay.netlify.app/) · [Code](https://github.com/shemthom31/Jamaica-Pay) |
| QuantTrade | React, TypeScript | [Live](https://quanttraders.netlify.app/) · [Code](https://github.com/shemthom31/QuantTrade) |
| StickyDesk | CSS, JavaScript | [Live](https://stickydeskpinboard.netlify.app/) · [Code](https://github.com/shemthom31/StickyDesk) |

---

## Usage

No installation or build step required.

```bash
# Clone or download the repo, then simply open the file
open index.html
```

Or drag `index.html` into any browser window.

---

## Deployment

Because it's a single static HTML file it can be deployed anywhere:

- **Netlify** — drag the folder into the Netlify dashboard
- **GitHub Pages** — push to a repo and enable Pages from the repository settings
- **Vercel** — import the repo and deploy with zero configuration

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Scripting | Vanilla JavaScript (ES6+, IntersectionObserver, CSS transitions) |
| Fonts | Inter + JetBrains Mono via Google Fonts |

---

## Customisation

All content lives directly in `index.html`. Key areas to update:

- **Personal details** — hero section, contact links, footer
- **Projects** — the `PROJECTS` object in the `<script>` block at the bottom of the file controls all modal content
- **Skills** — skill category cards in the Skills section
- **LinkedIn URL** — search for `linkedin.com/in/shemar-thompson-791842189` to find all instances

---

## Contact

**Shemar Thompson**
shemarthompson007@gmail.com
[linkedin.com/in/shemar-thompson-791842189](https://www.linkedin.com/in/shemar-thompson-791842189)
