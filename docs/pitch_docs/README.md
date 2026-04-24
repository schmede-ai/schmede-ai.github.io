# Wrath — Frontispiece (Web)

Standalone web version of the Wrath frontispiece. Designed to be dropped under `/docs/` on a GitHub repo for GitHub Pages serving.

## Structure

```
pitch_docs/
├── index.html          single scrollable deck; all 25 pages stacked
├── css/
│   └── base.css
├── fonts/
│   ├── Cinzel-Regular.ttf
│   ├── Cinzel-Bold.ttf
│   ├── EBGaramond-Regular.ttf
│   ├── EBGaramond-Italic.ttf
│   ├── CormorantGaramond.ttf
│   └── UnifrakturMaguntia.ttf
└── images/
    ├── cover/
    ├── heaven/
    ├── hell/
    ├── powers/
    └── world/              (cosmology.png preserved; others JPEG q85)
```

Total size: ~20 MB.

## Deployment

Drop the entire folder into your repo under `docs/` (or wherever GitHub Pages is configured to serve from). No build step required — static HTML + CSS + assets.

## Editing

All layout is driven by `css/base.css`. Per-page HTML is inlined in `index.html` — open that file to edit any page's content.
