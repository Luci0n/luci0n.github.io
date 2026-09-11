# luci0n.github.io

Landing page for https://luci0n.github.io/ — links to the live pages and the
repositories behind them.

Plain HTML and CSS with one small script for the language filter. No build
step, no dependencies, no third-party requests: JetBrains Mono is served from
`assets/fonts/`, so nothing is fetched from Google.

```
index.html                 the page
assets/*.webp              screenshots used on the cards
assets/fonts/*.woff2       JetBrains Mono (latin, latin-ext)
```

Edit `index.html` and push; GitHub Pages serves `main` at the root.
