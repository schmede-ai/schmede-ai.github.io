# Wrath — Frontispiece (Web)

Standalone web version of the Wrath frontispiece. Drops into `/docs/` on
the GitHub Pages repo as the replacement for the previous pitch deck.

## Structure

```
frontispiece_docs/
├── index.html          single scrollable deck; all 17 pages stacked
├── css/
│   └── base.css
├── fonts/              Cinzel, EB Garamond, Cormorant, Unifraktur (TTF)
└── images/             cover, world, heaven, powers, paintings, hell
```

## Deploy

Drop the entire folder into your GitHub repo at the same path the previous
pitch deck lived (e.g. `docs/wrath-pitch/`), overwriting. The URL path
stays the same so any inbound links continue to work.

## Notes

- The cover hosts a lazy YouTube embed for the trailer (video ID
  `RcJJOw__tIc`). Embed only works once the video is public AND the page
  is served over HTTPS (i.e. live on GitHub Pages, not local file://).
- Each page section has an anchor id (`#cover`, `#epigraph`, `#powers`,
  `#sacrilega`, etc.) so a future sidebar can deep-link into the deck.
