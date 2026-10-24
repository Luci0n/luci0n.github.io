# luci0n.github.io

Portfolio for https://luci0n.github.io/: write-ups of selected public projects
and contact details.

Plain HTML and CSS with no JavaScript on the landing page itself. No build
step, no dependencies, no third-party requests: JetBrains Mono is served from
`assets/fonts/`, so nothing is fetched from Google.

```
index.html                 the page
assets/*.webp              screenshots used in the selected work section
assets/fonts/*.woff2       JetBrains Mono (latin, latin-ext)
```

Edit `index.html` and push; GitHub Pages serves `main` at the root.

To feature a new public project, add an entry under `Selected work`.
The CrowFX tiles are CSS approximations, so they need no image file.

## CrowPSX

- [Product website](https://luci0n.github.io/crowpsx/)
- [Documentation](https://luci0n.github.io/crowpsx/docs/)
- [Unity PSX shader comparison](https://luci0n.github.io/crowpsx/guides/psx-shaders-unity-comparison/)

The root sitemap includes the CrowPSX product, guides, and documentation pages.
