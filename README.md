# Frieren.studio — Motion Design Studio Portfolio

Awwwards-level portfolio for a motion design studio. Built with clean HTML/CSS/JS, Lenis smooth scroll, and GSAP animations.

## 🚀 Quick Start

### 1. Add your videos
Edit the `VIDEO CONFIG` block at the top of `public/index.html` (lines ~9-55):

```javascript
window.FRIEREN_CONFIG = {
  heroReel: [
    { video: 'https://your-cdn.com/brand-films.mp4', poster: '', label: 'Brand Films' },
    // ...
  ],
  aboutReel: { video: 'https://your-cdn.com/studio-reel.mp4', poster: '' },
  // ...
};
```

### 2. Deploy to Vercel
```bash
npm i -g vercel
vercel
```

Or drag-and-drop `public/index.html` onto [vercel.com](https://vercel.com).

### 3. Connect a custom domain
In Vercel dashboard → Settings → Domains → `frieren.studio`

## 🧩 Sections
- **Hero** — mouse-reactive horizontal showreel + "A / Seriously / Good" type lockup
- **About** — sticky video + passion statement
- **Work** — dark cards with cover image, hover video reveal, LCD tag marquee
- **Services** — 3-column dark section with chip tags and clip-path image reveals
- **Letter scroll** — "MOTION DESIGNER" parallax letter animation
- **Tools grid** — cursor-following highlight
- **Footer** — frosted glass card grid with watermark

## 🛠 Tech
- Lenis smooth scroll
- GSAP + ScrollTrigger
- CSS clip-path reveals
- No build step, no dependencies to install

## 📁 Structure
```
├── public/
│   └── index.html     ← the whole site
├── vercel.json
├── .gitignore
└── README.md
```
