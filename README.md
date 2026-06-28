# Manthan Shende — Portfolio Website

> A highly polished personal portfolio for **Manthan Sunil Shende**, Industrial IoT Engineer & Software Developer.

---

## 🚀 Tech Stack
- **Pure HTML5, CSS3, Vanilla JavaScript** — zero dependencies, zero build step
- **Vercel-ready** static deployment

## 📁 Project Structure

```
manthan-portfolio/
├── index.html      # Complete portfolio (all-in-one)
├── vercel.json     # Vercel deployment config
└── README.md       # This file
```

## ✨ Features
- ⚡ Dark industrial-tech color palette (deep grays + neon cyan/blue accents)
- 🎯 Smooth scroll with active section highlighting
- 🔤 Typing animation in the Hero section
- 🎞️ Scroll-reveal animations via IntersectionObserver
- 📱 Fully responsive (mobile hamburger menu included)
- ♿ Semantic HTML & ARIA attributes for accessibility
- 🔒 Security headers via `vercel.json`

## 📋 Sections
1. **Hero** — Name, title, tagline, CTA buttons, social links, stats
2. **About** — Education, focus areas, profile card
3. **Skills** — IoT/Embedded, Languages, Web, Dev Tools
4. **Experience** — Embedded System Intern @ Internpe (Jun–Jul 2026)
5. **Projects** — Smart Radar, Voice-Controlled Robot Car, Posture Guard AI
6. **Certifications** — CIH 2.0, HVAC&R Hackathon, API Development Workshop
7. **Contact** — Form + email + phone

## 🌐 Deploy on Vercel

### Option 1 — Vercel CLI
```bash
npm install -g vercel
vercel
```

### Option 2 — Vercel Dashboard (Recommended)
1. Push this folder to a **GitHub repository**
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your GitHub repo
4. Framework: **Other** (Static HTML)
5. Click **Deploy** ✅

## 🛠️ Customization Tips

| What to change | Where in `index.html` |
|---|---|
| LinkedIn URL | `href` on `#social-linkedin` and `#contact-linkedin-link` |
| GitHub URL | `href` on `#social-github` and `#contact-github-link` |
| Project GitHub links | `.project-card-footer` anchor tags |
| Contact form backend | Replace the `setTimeout` in the `submit` handler with **FormSubmit** or **EmailJS** |

### Connect the Contact Form (optional)
Replace the form action with [FormSubmit](https://formsubmit.co/):
```html
<form action="https://formsubmit.co/manthanshende13@gmail.com" method="POST">
```

---

© 2026 Manthan Sunil Shende
