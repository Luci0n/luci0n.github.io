# luci0n.github.io

Portfolio for https://luci0n.github.io/: write-ups of selected public projects
and contact details.

Plain HTML and CSS, plus one small inline script: a topographic background
ported from CrowStudies (`assets/topography.js` there) and a scroll reveal for
each section. Both pause or switch off under `prefers-reduced-motion`. No build
step, no dependencies, no third-party requests: JetBrains Mono is served from
`assets/fonts/`, so nothing is fetched from Google.

```
index.html                 the page
assets/*.webp              screenshots (CrowPSX, CrowFX, StatementCheck, crowq3, CrowStudies)
assets/fonts/*.woff2       JetBrains Mono (latin, latin-ext)
```

Edit `index.html` and push; GitHub Pages serves `main` at the root.

To feature a new public project, add a section inside `<main>` with
`class="rv"` so it fades in like the others. The FlashGuard pipeline and
results chart are plain HTML; their numbers come from FlashGuard's
`docs/SURFACE-FREQUENCY.md` and `CHANGELOG.md`.

## CrowPSX

- [Product website](https://luci0n.github.io/crowpsx/)
- [Documentation](https://luci0n.github.io/crowpsx/docs/)
- [Unity PSX shader comparison](https://luci0n.github.io/crowpsx/guides/psx-shaders-unity-comparison/)

The root sitemap includes the CrowPSX product, guides, and documentation pages.
