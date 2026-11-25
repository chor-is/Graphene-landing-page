# HiPER Graphene — Website (v2)

A 3-page static product website for **HiPER Graphene**: multilayer graphene and ready-to-use graphene solutions for industry.

## Pages

| File | Content |
|---|---|
| `index.html` | Home: about the company, what multilayer graphene is, properties, product range, industries |
| `products.html` | Products: Multilayer Graphene powder, Graphene Cement Solution 20X, HiPER Concrete Block, Anti-Bacteria Self-Cleaning Spray, FIR Screen Printing Ink, Thermal Coil Coating |
| `services.html` | R&D services: direct sale, custom formulation, contract manufacturing, technology licensing; partners |

Shared: `styles.css`, `script.js`. Images in `assets/images/` (HiPER logo and product images in `assets/images/hiper/`).

## To fill in

- Company phone number (not provided yet).

## Features

- TH / EN language switch (remembered in the browser)
- Responsive layout with a mobile menu
- Image lightbox (keyboard accessible), product jump bar on the products page
- Fonts: DM Sans (English), IBM Plex Sans Thai (Thai)
- Palette: `#0099FF` accent, `#000000`, `#FFFFFF`, `#E2E2E2`, `#33332F`

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8765
```

Then open http://localhost:8765.
