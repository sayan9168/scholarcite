# ScholarCite

### Lightweight, zero-cost, AI-free instant citation generator

Convert any DOI into **APA, MLA, IEEE, Harvard, and BibTeX** formats using the free Crossref API.

Built with **Vanilla JS + Tailwind CSS** — no backend, no API keys, no AI cost.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Frontend](https://img.shields.io/badge/Stack-Vanilla%20JS%20%2B%20Tailwind-06B6D4)](#)

---

## Why ScholarCite?

Most citation tools are either:
- Heavy (require accounts / paid plans), or
- Depend on AI that can hallucinate metadata.

ScholarCite is intentionally simple:

1. Paste a DOI
2. Fetch authoritative metadata from **Crossref**
3. Generate clean citations in multiple styles
4. Copy & paste into your paper

No accounts. No tracking. No AI.

---

## Features

- DOI → APA / MLA / IEEE / Harvard / BibTeX
- Uses official Crossref API (accurate metadata)
- Instant client-side generation
- Zero cost, zero backend
- Clean, responsive UI (Tailwind)
- Works offline after first load (static assets)

---

## Quick Start

```bash
git clone https://github.com/sayan9168/scholarcite.git
cd scholarcite

# Just open index.html in a browser
# or serve locally:
npx serve .
```

Or open the live demo if deployed.

---

## How it works

1. User enters a DOI (e.g. `10.1038/nature14539`)
2. App calls `https://api.crossref.org/works/{doi}`
3. Metadata is parsed and formatted into citation styles
4. Result is shown and can be copied with one click

---

## Supported Styles

| Style | Example use |
|-------|-------------|
| **APA** | Psychology, education |
| **MLA** | Humanities |
| **IEEE** | Engineering, CS |
| **Harvard** | Many universities |
| **BibTeX** | LaTeX / academic writing |

---

## Tech Stack

- Vanilla JavaScript (no framework)
- Tailwind CSS
- Crossref REST API

---

## License

MIT License © [Sayan Mahata](https://github.com/sayan9168)

---

<div align="center">

Built by [Sayan the researcher](https://github.com/sayan9168)

</div>
