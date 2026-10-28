# Monochrome Palette

A small web app for planning one-color (monochrome) paintings in water-mixable oil or acrylic.

Load a reference photo and it will:

- group the photo into 3–9 values and show them as a value map
- give a mixing ratio for each tone: your chosen color plus Titanium White, with a darker partner paint for the deepest tones
- compare two ways of mixing the darks: a same-family color (top scale) or the complement (bottom scale)
- let you add punch: contrast, overall brightness, and a brush to brighten one area
- show the value map full screen and save it as a PNG

Paints are set up for **Winsor & Newton Artisan** and **Cobra** water-mixable oils: Ultramarine, Phthalo Blue, Phthalo Green, Light Green (Cobra), Orange and Red.

Ratios come from a Kubelka–Munk paint-mixing model with typical pigment data. Treat them as a starting point and test each mix on a card against your reference.

## Install on your phone

1. Open the GitHub Pages address in Safari (iPhone/iPad) or Chrome (Android).
2. iPhone: tap **Share → Add to Home Screen**. Android: tap **⋮ → Install app**.
3. It opens full screen and works offline after the first visit. Photos never leave the device.

## Updating

Edit `index.html`, then change `VERSION` in `sw.js` (for example `monochrome-palette-v3`) so installed copies pick up the change.
