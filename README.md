# La French Tech Oslo

Website for the La French Tech Oslo community, built with [Astro](https://astro.build/) and deployed on Vercel.

## Local development

Requires Node.js and npm.

```sh
npm install
npm run dev
```

Open the local URL shown in the terminal (usually `http://localhost:4321`).

## Commands

```sh
npm run dev      # Start the development server
npm run build    # Create a production build
npm run preview  # Preview the production build locally
```

## Project structure

- `src/pages/index.astro` — homepage content, markup, and styles
- `src/pages/robots.txt.ts` — robots.txt endpoint
- `src/assets/` — images processed by Astro
- `public/` — static files served as-is
- `astro.config.mjs` — Astro, sitemap, and Vercel configuration

The production site is configured for [frenchtech.no](https://www.frenchtech.no/).
