# Wrightworks Studios

Simple Astro-based static site for Wrightworks Studios, ready to deploy to Cloudflare Pages.

## Local development

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
```

Astro outputs the built site to `dist/`.

## Cloudflare Pages

Use these settings when creating the Pages project:

- Build command: `npm run build`
- Build output directory: `dist`
- Node.js version: `22` or newer

## Where things live

- Home page (hero, the three apps, how we work, contact): `src/pages/index.astro`
- One app's block (icon, status, platforms, image, links): `src/components/Product.astro`
- Header, footer, metadata, colours and fonts: `src/layouts/Layout.astro`
- The ship and wordmark: `src/components/Lockup.astro` and `src/assets/ship.svg`
- App icons and screenshots: `public/images/` (webp, 1200 × 750 for screenshots)
- Fonts: Fraunces and Onest, self-hosted in `public/fonts/` under the SIL Open Font License

A push to `main` deploys the site to https://wrightworksstudios.com.
