# Mein Scope — Marketing Website

Marketing site for [Mein Scope](https://github.com/K15W3G/Mein-Scope), an offline-first PWA for
endoscopy and colonoscopy patient intake, capture, and reporting. This is a separate repo from the
clinical app itself.

Built with [Astro](https://astro.build) + [Tailwind CSS v4](https://tailwindcss.com), styled with
a design language inspired by [alignui.com](https://alignui.com) and mapped onto the Mein Scope
brand palette.

## Structure

```
src/
├── assets/logo/     brand logo assets (icon + full wordmark)
├── components/       Nav, Footer, Icon
├── layouts/Layout.astro
├── pages/            index, features, pricing, about, faq, contact
└── styles/global.css Tailwind theme tokens + brand colors/utilities

docs/
├── BRAND-BRIEF.md    original product/brand brief
└── copy/             page-by-page copy drafts with rationale, pre-dating the .astro build
```

## Brand

- Primary: `#52B1E8` · CTA gradient: `#1D95DA → #52B1E8` · Wordmark accent: `#3F3D56`
- Typeface: Inter Variable, self-hosted via `@fontsource-variable/inter` (no external font requests)

## Known placeholders to swap before launch

- Home page app-preview panel (`src/pages/index.astro`) is a styled placeholder; swap in a real product screenshot.
- No self-serve pricing/signup exists yet by design — see `docs/copy/pricing.md` for why.

## Commands

| Command           | Action                                      |
| :----------------- | :------------------------------------------- |
| `npm install`       | Install dependencies                         |
| `npm run dev`       | Start local dev server at `localhost:4321`   |
| `npm run build`     | Build production site to `./dist/`           |
| `npm run preview`   | Preview the production build locally         |
