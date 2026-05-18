# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Previewing pages

No build step. Open any HTML file directly in a browser, or serve locally:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Architecture

This is a **pure HTML/CSS/JS** project — no frameworks, no bundler, no npm. Every page is a single self-contained `.html` file with all styles in a `<style>` block and all logic in `<script>` tags. There are no shared CSS or JS files between pages.

### File structure

```
/
├── index.html                        # Site index / hub
├── assets/
│   ├── Icon.svg
│   └── Lingocare_logo_transparent.png
├── fonts/                            # Local Montserrat + Sora (unused — Google Fonts is active source)
├── pages/                            # Active pages
│   ├── landing-page-lc.html          # Primary marketing landing page (DE/EN)
│   ├── exercise-components.html      # Exercise type UI component atlas
│   ├── lingocareai2.html             # Proprietary LLM strategy & build report v2 (latest)
│   ├── mvp_dashboard.html            # MVP progress dashboard
│   └── mvp-plan.html                 # Internal MVP build plan
└── archive/                          # Superseded versions
    ├── lingocareai.html              # LLM strategy report v1
    ├── landing-page-lc-old.html
    └── component-atlas-old.html
```

### Design system (replicate in every new page)

CSS custom properties are **redefined in each file's `:root`** — copy these exactly when creating a new page:

```css
:root {
  --bg: #FAF7F2;  --card: #FFFFFF;
  --orange: #F4722B;  --orange-light: rgba(244,114,43,0.09);
  --dark: #1A1208;  --mid: #5C4A38;  --muted: #9B8B7A;
  --border: #EBE0D0;  --border-light: #F2EBE0;
  --green: #2D8C5E;  --green-light: rgba(45,140,94,0.10);
  --red: #DC3C28;  --purple: #7C3AED;
  --font-d: 'Instrument Serif', Georgia, serif;  /* headings */
  --font-b: 'Outfit', sans-serif;                /* body */
  --s-sm: 0 1px 4px rgba(28,20,16,0.06), 0 2px 8px rgba(28,20,16,0.04);
  --s-md: 0 4px 16px rgba(28,20,16,0.08), 0 2px 6px rgba(28,20,16,0.05);
  --s-lg: 0 8px 32px rgba(28,20,16,0.10), 0 2px 8px rgba(28,20,16,0.06);
  --r: 14px;  --r-sm: 8px;
}
```

Google Fonts import (always include both):
```html
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Local fonts (Montserrat + Sora) are available in `fonts/` but are not currently used in any page — Google Fonts is the active source.

### i18n (landing page)

`pages/landing-page-lc.html` has a bilingual DE/EN system:
- All user-visible text lives in `const T = { de: {...}, en: {...} }` at the top of the `<script>` block (around line 358).
- HTML elements that need translation carry `data-t="key"` attributes — no text is hardcoded in the markup.
- `applyLang()` sets `innerHTML` of every `[data-t]` element from `T[lang]`.
- `switchLang(l)` fades out text (150ms), calls `applyLang()`, then reinitializes chat animations.
- Default language is `de`. No localStorage persistence.

When adding new translatable strings: add the key to **both** `T.de` and `T.en`, then use `data-t="key"` in the HTML.

### Common JS patterns

**Scroll reveal** — used in every page:
```js
const ro = new IntersectionObserver(entries => {
  entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('in'); });
}, { threshold: 0.12 });
document.querySelectorAll('.rev').forEach(el => ro.observe(el));
```
Add `.rev` class to any element; pair with `.d1`–`.d5` for staggered delays.

**Hide-on-scroll nav** — sticky nav hides on scroll-down, reveals on scroll-up using `nav.hidden` / `nav.scrolled` classes.

### Logo assets

- `assets/Icon.svg` — full wordmark SVG (56×32). Dark-brown text paths use `#47280A`; brand mark paths use `#EC8600`. When placing on a dark background, override text path fills to `rgba(250,247,242,0.8)`.
- `assets/Lingocare_logo_transparent.png` — raster version for contexts where SVG isn't suitable.
