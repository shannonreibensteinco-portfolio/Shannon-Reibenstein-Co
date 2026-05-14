# Shannon Reibenstein Co. — Website Prototypes

Possibilitarian For Hire. Brand voice strategy and contrarian messaging.

**Live site:** Deploy via Vercel — connect this repo and it's live in 60 seconds.

---

## Pages

| File | Route | Description |
|------|-------|-------------|
| `index.html` | `/` | Homepage |
| `about.html` | `/about` | About |
| `offers.html` | `/offers` | Work With Me + Inquiry Form |
| `work.html` | `/work` | Social Proof + Case Studies |
| `blog.html` | `/blog` | Field Notes |
| `art-direction.html` | `/art-direction` | Art Direction Reference Tool |
| `intake-form.html` | `/intake` | Standalone Inquiry Form |

---

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import this GitHub repo
4. Leave all settings as default — Vercel detects static HTML automatically
5. Click Deploy

Every push to `main` auto-deploys.

---

## Deploy to GitHub Pages (alternative)

1. Go to repo Settings → Pages
2. Set source to **main branch / root**
3. Live at `https://yourusername.github.io/repo-name`

---

## Color System

| Token | Hex | Usage |
|-------|-----|-------|
| Near Black | `#1F1B16` | Primary dark background |
| Slate Navy | `#2F364C` | Secondary backgrounds |
| Deep Purple | `#532263` | Accent, overlines on light |
| Dark Purple | `#6C0465` | Accent backgrounds |
| Deep Navy | `#04316C` | Accent backgrounds |
| Magenta | `#FC19E5` | Primary accent, CTAs |
| Magenta Soft | `#fe66c4` | Secondary accent on dark |
| Magenta Deep | `#9e1460` | Accents on light bg (AAA) |
| Off White | `#FEFCF8` | Primary text on dark / light bg |
| Warm Gray | `#B3A6A7` | Muted text on dark |
| Light Lilac | `#f5eef8` | Light section backgrounds |

All text combinations are WCAG AA compliant. Primary text combinations are AAA.

---

## Tech

- React 18 via CDN
- Babel Standalone for JSX
- No build step required
- Images embedded as base64
- Google Fonts: Anton

