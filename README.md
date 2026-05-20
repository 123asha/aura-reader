# AURA Reader — chapter prototype

Working prototype of the AURA Book chapter-reading screen per the design brief in `DESIGN-BRIEF.md` (not in this repo — lives separately).

## What's in here

- **`chapter-v1.html`** — single-file HTML + inline CSS + JS for the chapter reading page. Open directly in a browser, or serve the folder over HTTP for the local image references.
- **`images/`** — chapter images (downloaded from zamesin.ru source).

## Run locally

```bash
npx serve -l 5190 .
# then open http://localhost:5190/chapter-v1.html
```

## Fonts

- **Source Serif 4** (body) — Google Fonts, OFL
- **General Sans** (headings, labels) — Fontshare, free for commercial use
- **JetBrains Mono** (inline code, ASCII icons) — Google Fonts, Apache 2.0

All three are free for commercial use. Loaded over the network from their respective CDNs at runtime.

## Demo content

The chapter text is a translation of an existing Russian chapter from [zamesin.ru/producthowto/book](https://zamesin.ru/producthowto/book/introduction-to-advanced-jobs-to-be-done/), used as a canonical sample for styling all the content-block types listed in the brief §7.4.
