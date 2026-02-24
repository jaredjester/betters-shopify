# HydroShell SwimBuds Theme

A customized Shopify theme (based on the Publisher template) for the HydroShell™ SwimBuds waterproof earphones. It includes hero, lifestyle, feature, bundle, and testimonial sections tailored to the $60 waterproof earbuds plus bundle pricing ($100 for two with one free gift, $120 for three with two gifts).

## Highlights

- **New custom sections** (`sections/waterbuds-*.liquid`) for hero, lifestyle imagery, feature cards, bundle table, and 12 hand-written reviews that mention initial waterproof doubts.
- **Preloaded imagery** (`assets/hero-swimmer.jpg`, `swimmers-duo.jpg`, `pool-runner.jpg`) showcasing swimmers wearing the buds.
- **Homepage (`templates/index.json`)** restructured to focus solely on the HydroShell product story.
- **Product template (`templates/product.json`)** extended with feature proof points, bundle pricing, and testimonials directly on the PDP.

## Bundle logic

| Pack | Price | Gifts |
| --- | --- | --- |
| Solo | $60 | HydroShell case |
| Wave Duo | $100 | Waterproof carry pouch |
| Squad Trio | $120 (double the base price) | Floating dry bag + anti-fog swim cap |

## Colorways

- Ripcurrent Blue
- Ultraviolet Purple
- Midnight Black

## Getting started

1. Copy this folder into your Shopify theme (or upload as a new theme).
2. In the theme editor, ensure your HydroShell product handle is `/products/hydroshell-swimbuds` or update the CTA links in `waterbuds-hero.liquid` / `templates/index.json`.
3. The hero and lifestyle sections ship with bundled imagery. Swap them in the theme editor if you have brand photography.
4. Update the reviews or feature copy in the custom sections if you need store-specific language.

## Development

```
npm install -g @shopify/cli @shopify/theme
shopify theme dev --store your-store
```

## Assets

All images come from Unsplash and are stored locally inside `assets/` so they deploy with the theme.
