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

## Quick content edits

- Main page content: `src/pages/index.astro`
- Shared document shell and metadata: `src/layouts/Layout.astro`
