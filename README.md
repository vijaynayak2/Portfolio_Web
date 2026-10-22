# Vijay S Nayak — Portfolio Website

A personal portfolio website built as a static site (HTML + CSS + JavaScript). No build tools or server required.

---

## Running Locally

### Option 1 — Open directly in browser (simplest)
Double-click `index.html` to open it in your default browser.

> **Note:** Google Fonts (Inter & JetBrains Mono) require an internet connection to load. The site still works offline but will fall back to system fonts.

### Option 2 — Local development server (recommended)

If you have **Node.js** installed:

```bash
npx serve .
```

Then open `http://localhost:3000` in your browser.

Alternatively, with **Python**:

```bash
# Python 3
python -m http.server 8080
```

Then open `http://localhost:8080`.

---

## Project Structure

```
portfolio/
├── index.html          ← Main HTML (all sections)
├── css/
│   └── style.css       ← All styles (theme, layout, responsive)
├── js/
│   └── main.js         ← Interactivity (navbar, scroll spy, animations)
└── README.md           ← This file
```

---

## Updating Resume Content

All personal content lives in `index.html`. Each section is clearly commented:

| Section | HTML comment to find |
|---|---|
| Hero | `<!-- HERO -->` |
| About | `<!-- ABOUT -->` |
| Education | `<!-- EDUCATION -->` |
| Projects | `<!-- PROJECTS -->` |
| Skills | `<!-- SKILLS -->` |
| Achievements | `<!-- ACHIEVEMENTS -->` |
| Contact | `<!-- CONTACT -->` |

### Common updates:
- **Email / Phone:** Search for `vijaynayak2111@gmail.com` and `+91 6364080799`
- **Add a project link:** Find the relevant project card and replace the `<!-- Project link: add URL here -->` comment with an `<a>` tag
- **Add GitHub/LinkedIn:** Find the contact section and add anchor tags with your real profile URLs

---

## Technology Stack

| Layer | Choice | Reason |
|---|---|---|
| Markup | HTML5 (semantic) | No dependencies, maximum compatibility |
| Styling | CSS3 (custom properties, grid, flexbox) | Full control, no framework overhead |
| Scripting | Vanilla JavaScript (ES6+) | Lightweight, no build step |
| Fonts | Google Fonts (Inter + JetBrains Mono) | High-quality typography via CDN |

No framework, no bundler, no build step. Just open and run.

---

## Items Awaiting Your Confirmation

| # | Issue | Current Treatment |
|---|---|---|
| 1 | Resume header says "Marketing Manager" — conflicts with AI/ML student profile | Omitted; used actual profile description |
| 2 | Pre-University (2022–2024) and SSLC (2022–2024) share identical dates | Displayed as-is with a visible caution note |
| 3 | "Student Performance Prediction" listed as "2030 – PRESENT" (future date) | Displayed as "Ongoing" without the erroneous year |
| 4 | `www.reallygreatsite.com` is a template placeholder | Omitted entirely |
| 5 | GitHub / LinkedIn / Project URLs | Placeholders in comments — add your real links |

---

## Deployment (Optional)

### GitHub Pages (free)
1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages → Source → Deploy from branch (main)**.
3. Your site will be live at `https://<your-username>.github.io/<repo-name>`.

### Netlify (free, drag-and-drop)
1. Go to [netlify.com](https://www.netlify.com/).
2. Drag the `portfolio/` folder onto the deploy area.
3. Your site is live in seconds.

---

*Portfolio built for Vijay S Nayak — content sourced exclusively from the uploaded resume.*
