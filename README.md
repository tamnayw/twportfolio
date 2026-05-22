# ✦ Personal Portfolio

A clean, editorial style personal portfolio website,  built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies. Just one file.

---

## Preview

> Live at: [tamnayw.github.io](https://tamnayw.github.io)

---

## Features

- **GitHub API integration** — repos load automatically from your profile
- **Editorial design** — Cormorant Garamond + Jost typography, cool minimal palette
- **Electronic background** — Dot grid aesthetic
- **Scroll animations** — lightweight IntersectionObserver reveals
- **Frosted glass nav** — activates on scroll
- **Fully responsive** — mobile-first breakpoints
- **Zero dependencies** — one HTML file, works anywhere

---

## Getting Started

No install needed. Just open `portfolio.html` in a browser.

```bash
git clone https://github.com/tamnayw/tamnayw.github.io.git
cd tamnayw.github.io
open portfolio.html
```

---

## Customization

All editable sections are marked with `CUSTOMIZE` comments inside the file.

| What | Where in code |
|---|---|
| Your name | `<title>`, `.nav-brand`, `.hero-name`, `footer` |
| GitHub username | `const GITHUB_USERNAME = 'yourusername'` |
| Tagline & bio | `.hero-tagline`, `.about-body` |
| Disciplines | `<span class="discipline">` tags |
| Contact links | `.contact-line` rows |
| Accent color | `--accent` and `--accent-dark` in `:root` |
| Repos to exclude | `const EXCLUDE_REPOS = []` |
| Max repos shown | `const MAX_REPOS = 9` |

---

## Deployment

Hosted on **GitHub Pages** — free, automatic, no config needed.

1. Push to a repo named `tamnayw.github.io`
2. Go to **Settings → Pages → Source → main branch**
3. Live in ~60 seconds at `https://tamnayw.github.io`

To update the site:

```bash
git add .
git commit -m "your message"
git push
```

Or use the **VS Code Source Control** tab — stage, commit, sync in a few clicks.

---

## Project Structure

```
/
└── index.html      ← everything lives here
└── README.md
└── logo.svg        ← optional, drop in your logo
└── resume.pdf      ← optional, link it in the contact section
```

---

## Tech

- HTML5 / CSS3 / Vanilla JS
- [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Jost](https://fonts.google.com/specimen/Jost) via Google Fonts
- [GitHub REST API v3](https://docs.github.com/en/rest) — public, no auth required

---


