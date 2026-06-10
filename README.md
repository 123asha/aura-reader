# Skip Design

Working prototype of the AURA Book chapter-reading screen per the design brief in `DESIGN-BRIEF.md` (not in this repo — lives separately).

## Tone of voice — my reading of §10.2

*editorial-restrained · book-on-screen · Krichevsky-disciplined.*

The variant leans on **typographic discipline over visual flair**: serif body (Source Serif 4) under sans labels (General Sans) reads like a book, not a blog feed. A single deep oxide-red accent (`#8B2A1E`) is reserved for links, the Skeptic icon, and footnote refs — never decoration. Hairlines, red-line paragraph indents, a calibrated 10/12/14/17 small-text scale, and tight 1.44 leading give the page Krichevsky-grade rhythm; Notion's airy whitespace keeps it from feeling printed-out.

Per the brief's character scales (serious · bold · rational · mature · progressive), the design avoids: cute, corporate-cold, academic-dusty, editorial-loud, dashboard-instrumental.

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
