# HOTBOXMALAYSIA™ — Official Website
### WD222 Multimedia Website — Final Project

> 🌐 **Live Preview:** [wd-222-hotbox-beatbox-malaysia.vercel.app](https://wd-222-hotbox-beatbox-malaysia.vercel.app/)

> 📁 **Repository:** [NeKoMaRu2607/WD222---HOTBOX-BEATBOX-MALAYSIA](https://github.com/NeKoMaRu2607/WD222---HOTBOX-BEATBOX-MALAYSIA)

A multi-page website for **HOTBOXMALAYSIA™**, Malaysia's premier beatbox community organisation. Built as a final project for the WD222 Web Design module.

---

## 📁 Project Structure

```
WD222 - Final Project/
├── index.html               # Landing page — entry point for GitHub Pages
├── Artists.html             # Artists showcase
├── Events.html              # Beatbox battle events
├── Contents.html            # Merchandise & content
├── Contact Us.html          # Contact form + map
├── Login Form.html          # Login page
├── Register Form.html       # Registration page
│
├── css/
│   ├── index.css            # Global styles — navbar, dropdowns, layout
│   ├── EVENTS styles.css    # Card flip effect & event page styles
│   ├── CU styles.css        # Contact Us page styles
│   └── FORM styles.css      # Login & Register form styles
│
├── js/
│   └── (empty — no custom scripts)
│
└── media/                   # All images, videos, and audio
    ├── Hotbox loop.mp4      # Hero background video
    ├── Battle_Balik Teaser.mp4  # Event teaser video
    ├── Hotbox Logo.jpg      # Navbar logo
    └── ...                  # Event posters, photos, merchandise images
```

---

## 🌐 Pages

| Page | Description |
|------|-------------|
| `index.html` | Hero video carousel, About Us, photo gallery, WhatsApp CTA |
| `Artists.html` | Solo artists, crew, loopstation & tag team listings |
| `Events.html` | Upcoming & past beatbox battle events with flip-card display |
| `Contents.html` | Merchandise shop items (sling bag, cap, tee) |
| `Contact Us.html` | Contact form with Malaysia map |
| `Login Form.html` | Member login |
| `Register Form.html` | New member registration |

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup across 7 pages
- **CSS3** — 4 stylesheets organised by page/feature (see CSS Architecture below)
- **Bootstrap 5.3** — responsive grid, navbar, offcanvas, carousel
- **Font Awesome 6.6** — icons throughout the site
- **jQuery 3.7** — Bootstrap 3 compatibility

---

## 🚀 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/NeKoMaRu2607/WD222---Multimedia-Website.git
   ```
2. Open `index.html` directly in your browser — no build step or server needed.

> **Note:** Videos and audio use relative paths, so always open files from the project root folder.

---

## 📝 CSS Architecture

Styles are split across 4 dedicated files, each scoped to its page or feature:

| File | Covers |
|------|--------|
| `css/index.css` | Global navbar, dropdown animation, layout — used by all pages |
| `css/EVENTS styles.css` | CSS variables, card flip effect — Events page only |
| `css/CU styles.css` | Form text and layout — Contact Us page only |
| `css/FORM styles.css` | Full reset, form layout, inputs — Login & Register pages |

---

## 👤 Author

**NeKoMaRu** — Diploma in Software Engineering, SBIT Training Academy
