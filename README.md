# SLRI Graphene Technology — Website

A 3-page static website presenting the graphene technology of the Synchrotron Light Research Institute (Public Organization), Thailand: turning carbon-based waste into high-value graphene with Long Pulse Joule Heating (LPJH).

## Pages

| File | Content |
|---|---|
| `index.html` | Home: key numbers, what graphene is, properties, process, why LPJH, applications |
| `research.html` | Research & Equipment: LPJH vs exfoliation, synthesizer specs, graphene powder specs, Raman / XPS / TEM / NEXAFS results, publication, patents |
| `activities.html` | Activities & Partners: Mitr Phol technology transfer, activity gallery, partners |

Shared: `styles.css`, `script.js`, images in `assets/images/`.

## Features

- TH / EN language switch (remembered in the browser)
- Responsive layout with a mobile menu
- Tabs, accordion and an image lightbox (keyboard accessible)
- Fonts: DM Sans (English), IBM Plex Sans Thai (Thai)
- Palette: `#0099FF` accent, `#000000`, `#FFFFFF`, `#E2E2E2`, `#33332F`

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8765
```

Then open http://localhost:8765.
