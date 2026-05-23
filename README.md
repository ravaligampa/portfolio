# 🌐 Ravali Gampa · Portfolio Website

A **single-file portfolio website** built with vanilla HTML, CSS, and JavaScript. Zero dependencies. Open anywhere. Host anywhere.

## ⚡ Quick start

```
Double-click index.html
```

The site opens in your browser, fully working, offline.

## ✨ Features

- **Dark cyberpunk-data theme** — cyan + violet gradient accents, particle network background
- **Animated hero** — typewriter cycling through your tech stack, count-up stats
- **Live particle background** — connected nodes, subtle motion (canvas-based)
- **8 sections:**
  - Hero — name + tagline + animated stats
  - About — story + leadership recognition quote
  - The Stack — categorized tech grid (AI, Languages, Big Data, Cloud, Streaming, DQ, Learning)
  - Selected Work — 4 flagship projects with metrics
  - Experience — timeline with Intuit subsections + Deloitte
  - Education & Certs — degrees + AWS cert + Udacity
  - Recognition — 4 leadership quote cards
  - Contact — email + LinkedIn + phone CTAs
- **Smooth-scroll navigation** with active section highlighting
- **Scroll-triggered reveal animations** on every section
- **Fully responsive** — mobile, tablet, desktop
- **Accessible** — semantic HTML, keyboard navigation, high color contrast
- **No tracking** — no analytics, no third-party scripts, no fonts loaded externally
- **Single file** — 1 HTML file, ~50 KB, fully self-contained

## 🚀 Hosting options (when you're ready to share publicly)

### Option 1: GitHub Pages (free, recommended)
1. Create new public repo on GitHub.com (personal account) named `ravali-gampa.github.io` or similar
2. Upload `index.html`
3. Settings → Pages → Source: main branch
4. Live at: `https://ravali-gampa.github.io/`

### Option 2: Netlify (free, drag-and-drop)
1. Go to https://app.netlify.com/drop
2. Drag the `portfolio/` folder onto the page
3. Live in 30 seconds at: `https://random-name.netlify.app`
4. Customize subdomain in Netlify settings

### Option 3: Vercel (free, drag-and-drop)
1. Go to https://vercel.com/new
2. Import / drag folder
3. Live at: `https://your-project.vercel.app`

### Option 4: Personal domain
- Buy domain (Namecheap, Google Domains, Cloudflare Registrar)
- Point DNS to GitHub Pages / Netlify / Vercel
- Live at: `https://ravaligampa.com`

## 🎨 Customizing

Open `index.html` in any text editor.

### Change the tech stack typed in hero
Find the `phrases` array near the bottom (in `<script>`):
```javascript
const phrases = [
  "Apache Spark + Delta Lake",
  "Claude Code + MCP",
  // add your own
];
```

### Change colors
Find `:root` at the top of `<style>`:
```css
--cyan: #00d9ff;
--violet: #a855f7;
--orange: #f97316;
```
Replace with your preferred palette.

### Add/remove projects
Find the `.projects-grid` section in `<body>`. Each `.project-card` is one entry. Copy/paste the pattern.

### Update contact info
Search for `ravaligampa13@gmail.com` and replace with your email. Same for phone, LinkedIn URL, location.

## 📦 File contents

```
portfolio/
├── index.html    ← The entire site (62 KB, self-contained)
└── README.md     ← This file
```

That's it. No build step. No node_modules. No CI/CD. Just one HTML file.

## 🔄 Sharing with someone

Send them `index.html`. They double-click. Done.

For online sharing: pick a hosting option above → 5 minutes → public URL.

## 🛠 Technical details

- **HTML5** semantic markup
- **CSS Custom Properties** for theming
- **CSS Grid + Flexbox** for layout
- **IntersectionObserver API** for scroll-triggered animations
- **Canvas API** for particle background
- **No frameworks** — vanilla JS only
- **No fonts loaded** — uses system font stack for speed
- **No images** — all visual elements via CSS / emoji / SVG
- **Browser support:** Chrome 90+, Safari 14+, Firefox 88+, Edge 90+

## 🎯 Recommended next steps

1. **Open it now:** `open ~/Documents/Layoff/portfolio/index.html`
2. **Personal review:** Read every section critically. Anything outdated, change in `index.html`.
3. **Get feedback:** Share with 2-3 trusted ex-colleagues for design + content critique.
4. **Push to GitHub Pages:** Make it live with a real URL — adds credibility on resume + LinkedIn.
5. **Add the URL to:**
   - Resume header (replace LinkedIn line with `ravaligampa.com` or similar)
   - LinkedIn "Featured" section
   - Email signature
   - Application form "Portfolio URL" fields

Live URL on resume signals seriousness. Even better: a portfolio URL that looks designed and intentional (not generic LinkedIn dump).

## 💡 Pro tips

- **First impression:** The hero stat counters are designed to make recruiters stop scrolling. Don't change them.
- **Recognition section:** Pulls weight at senior+ levels — most candidates don't have quotes from CTOs and Senior Directors. Lead with this in interviews.
- **Tech stack categories:** Recruiters search for keywords. Make sure every tool they care about appears in your tags.
- **Projects vs Experience:** Projects = case studies (focused, metrics-heavy). Experience timeline = breadth + tenure proof. Both serve different recruiter scans.

---

Built in one session, May 2026. Free to use, modify, host anywhere. Good luck on your search.
