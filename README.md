# safar-byte.github.io

Source for my portfolio at **[safar-byte.github.io](https://safar-byte.github.io)**.

A single static page — no framework, no build step. The hero draws my work history as a trace waterfall (the span chart you'd see in an observability tool); select a span to see what it was.

- `index.html` — markup, styles and the small script that draws the trace
- Fonts: Schibsted Grotesk and IBM Plex Mono from Google Fonts
- Light and dark mode follow the system setting; motion is skipped when reduced motion is on

To add a project to the trace, append an entry to the `spans` array near the bottom of `index.html`.

Deployed automatically by GitHub Pages from the `master` branch.

**Muhammed Safar** — [@safar-byte](https://github.com/safar-byte)
