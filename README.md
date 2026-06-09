# Lingocare.ai

Marketing and documentation hub for **Lingocare** — an AI-powered learning platform for German nursing schools (*Pflegeschulen*).

## Quick start

No build step. Open any HTML file directly, or serve locally:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Architecture

Pure **HTML/CSS/JS** — no frameworks, no bundler, no npm. Every page is a self-contained `.html` file with embedded `<style>` and `<script>` blocks. No shared CSS or JS files between pages.

### Design system

CSS custom properties live in each file's `:root`. When creating a new page, copy from an existing one. Google Fonts (Montserrat + Roboto or Instrument Serif + Outfit, depending on the page) are loaded via CDN. Local fonts in `fonts/` are available but not currently used.

## Repository structure

```
/
├── index.html                          # Site index — card-based navigation hub
├── pages/
│   ├── landing-page-lc.html            # Primary marketing page (DE/EN bilingual)
│   ├── demo.html                       # Interactive platform demo
│   ├── lingocareai2.html               # Proprietary LLM strategy & build report v2
│   ├── mvp-plan.html                   # Internal MVP roadmap and build plan
│   ├── exercise-components.html        # Exercise type UI component atlas
│   ├── doc-viewer.html                 # Universal markdown document viewer
│   └── curriculum.json                 # Curriculum data (JSON)
├── docs/
│   ├── lingocare_app_vision.md         # Product vision — all seven roles, AI layer, platform
│   ├── lingocare_learner_deepdive.md   # Learner experience deep-dive (v2)
│   ├── lingocare_instructor_deepdive.md # Instructor experience deep-dive (v2)
│   ├── lingocare_schooladmin_deepdive.md # School Admin experience deep-dive (v1)
│   └── Feedback/                       # User research and review feedback
├── archive/                            # Superseded versions kept for reference
│   ├── lingocareai.html                # LLM strategy v1
│   ├── landing-page-lc-old.html        # Landing page v1
│   ├── component-atlas-old.html        # Component atlas v1
│   └── mvp_dashboard.html              # Deprecated MVP dashboard
├── assets/                             # Logos and mascot images
├── fonts/                              # Local Montserrat + Sora (unused)
├── CLAUDE.md                           # Development guide for Claude Code
└── README.md
```

## Document viewer

`pages/doc-viewer.html` renders any markdown file from the `docs/` directory in a responsive reader layout with:

- Sticky header with download button
- Auto-generated table of contents sidebar (h2/h3 headings)
- Smooth-scroll navigation with active link highlighting
- GFM-style heading anchor IDs

Usage: `pages/doc-viewer.html?file=lingocare_app_vision.md`

## Docs series

Four interconnected documents cover every platform role:

| Document | Role | Pages |
|----------|------|-------|
| [App Vision](docs/lingocare_app_vision.md) | All roles | 54 KB |
| [Learner Deep-Dive](docs/lingocare_learner_deepdive.md) | Learner | 48 KB |
| [Instructor Deep-Dive](docs/lingocare_instructor_deepdive.md) | Instructor | 70 KB |
| [School Admin Deep-Dive](docs/lingocare_schooladmin_deepdive.md) | School Admin | 53 KB |

## Brand

- **Primary orange:** `#ED7D00`
- **Dark:** `#1A1208`
- **Background:** `#FAF7F2`
- **Heading font:** Montserrat (800 weight for display)
- **Body font:** Roboto

Logos in `assets/`: SVG wordmark (`Icon.svg`), raster fallback (`Lingocarelogowhitebg.png`), light-on-dark variant (`lingolight.png`).
