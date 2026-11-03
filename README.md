# Sri Udupi Park — Digital Menu Website

A mobile-first digital menu website for **Sri Udupi Park Veg Family Restaurant** (ಶ್ರೀ ಉಡುಪಿ ಪಾರ್ಕ್), designed to be opened directly from a **QR code** — no app, no login.

## Features
- 📱 Mobile-first (320px → 1440px responsive, tested with zero overflow/overlap issues)
- 🚀 Single-file, zero-external-dependency build (~30 KB) — fast on mobile data
- 🔍 Live menu search + horizontally scrollable category chips
- 💰 123 menu items with consistent right-aligned prices across 12 categories
- 🥬 Pure-Veg branding with printed-menu timings (breakfast / lunch / tiffin / dinner)
- ♿ Lighthouse: Accessibility 100 · Best Practices 100 · SEO 100

## Deployment

### Vercel
1. Push/merge to the `main` branch of this repository.
2. On [vercel.com/new](https://vercel.com/new), import the GitHub repo `AbhishekHosamani123/Sri-Udupi-Park-Menu`.
3. Accept the default framework preset (**Other / Static**) — no build command or output directory required.
4. Deploy. Update the printed QR codes to point to the production URL.

### Local preview
Just open `index.html` in any browser, or run:
```bash
python -m http.server 8080
# then visit http://localhost:8080
```

## Structure
```
index.html   # complete site (HTML + CSS + JS inline, menu data in JS)
```

Menu last updated: Nov 2026.
