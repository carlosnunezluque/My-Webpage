# 🖥️ Carlos Núñez Luque — Personal Portfolio

[![Live](https://img.shields.io/badge/status-live-38bdf8?style=flat-square&logo=vercel)](https://github.com/carlosnunezluque)
[![HTML](https://img.shields.io/badge/HTML-vanilla-e34f26?style=flat-square&logo=html5&logoColor=white)](https://github.com/carlosnunezluque)
[![CSS](https://img.shields.io/badge/CSS-vanilla-264de4?style=flat-square&logo=css3&logoColor=white)](https://github.com/carlosnunezluque)
[![JS](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?style=flat-square&logo=javascript&logoColor=black)](https://github.com/carlosnunezluque)

Personal portfolio website built entirely from scratch with no frameworks — pure HTML, CSS and JavaScript in a single file.

---

## 👤 About me

I'm a 19-year-old SysAdmin from Málaga, Spain, currently studying a Higher National Diploma in Network Systems Administration (ASIR). Passionate about Linux, infrastructure, automation and cloud technologies. Open to new opportunities — remote, hybrid or on-site.

---

## ✨ Features

- **Preloader** — animated intro with name reveal
- **Glassmorphism navbar** — scroll-aware, with preferences dropdown (language + theme), CV download dropdown and mobile hamburger menu
- **Dark / Light mode** — persisted in `localStorage`
- **Multilingual (ES / EN / DE)** — full i18n coverage across all sections, persisted in `localStorage`
- **Hero section** — terminal visual, animated gradient text, floating badge
- **About** — bio, tech stack chips, stats
- **Projects** — filterable card grid (Cloud / DevOps / Security)
- **Journey** — experience and education timeline
- **Contact** — info card with copy-to-clipboard, contact form via Formspree
- **AI Chatbot** — floating assistant powered by Claude (Anthropic API), answers questions about me in any language, auto-detects the visitor's language
- **Fully responsive** — optimised for all screen sizes
- **Smooth animations** — reveal on scroll, keyframe-based transitions, animated gradient

---

## 🛠️ Tech stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, keyframes) |
| Logic | Vanilla JavaScript (ES2020+) |
| Icons | Font Awesome 6 |
| Fonts | Space Mono · DM Sans (Google Fonts) |
| Form | Formspree |
| AI | Anthropic Claude API |
| Images | Unsplash |

---

## 📁 Project structure

```
portfolio/
├── index.html          # Entire site — markup, styles and scripts in one file
├── README.md
├── carlos-nunez-luque-cv-es.pdf   # CV in Spanish (add your own)
├── carlos-nunez-luque-cv-en.pdf   # CV in English (add your own)
└── carlos-nunez-luque-cv-de.pdf   # CV in German (add your own)
```

> The three CV files are not included in this repository. Place your own PDFs in the root directory with the exact filenames above for the CV download buttons to work.

---

## 🚀 Setup

No build step, no dependencies, no npm. Just open `index.html` in a browser.

```bash
git clone https://github.com/carlosnunezluque/portfolio.git
cd portfolio
open index.html
```

To deploy, upload `index.html` and your CV PDFs to any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

---

## 🤖 AI Chatbot

The floating chatbot uses the **Anthropic Claude API** to answer visitor questions about my experience, skills and availability. It auto-detects the visitor's language (Spanish, English or German) and responds accordingly.

> **Note:** The API call is made client-side. For production use, route requests through a backend proxy to keep your API key secure — never expose it directly in the frontend.

---

## 📬 Contact

- **Email:** nunezluquec08@gmail.com
- **LinkedIn:** [carlos-núñez-luque](https://www.linkedin.com/in/carlos-núñez-luque-98b085343)
- **GitHub:** [carlosnunezluque](https://github.com/carlosnunezluque)

---

<p align="center">
  Built with care — Málaga, Spain 🇪🇸
</p>
