# Farah Nasser Portfolio

A responsive, accessible portfolio built with React, TypeScript, and Vite. Personal details and project information are kept to the facts provided in the source brief.

## Requirements

- Node.js 20.19+ or 22.12+
- npm

## Install and run

```sh
npm install
npm run dev
```

Vite prints the local development URL after startup.

## Build and preview

```sh
npm run build
npm run preview
```

The deployable static site is generated in `dist/`.

## Deploy

Deploy the contents of `dist/` to any static hosting provider, including Vercel, Netlify, or GitHub Pages. For a provider with a build configuration, use `npm run build` as the build command and `dist` as the output directory. No server-side environment variables are required.

## Update the portfolio

- `src/App.tsx`: name, biography, contact details, navigation, skill groups, education, training, focus areas, and project content.
- `src/styles.css`: layout, typography, colors, responsive behavior, and light/dark themes.
- `public/favicon.svg`: browser icon.
- `public/og-image.svg`: social sharing preview artwork.
- `index.html`: title, SEO/social metadata, canonical URL, and font loading.
- `public/robots.txt` and `public/sitemap.xml`: update the example domain before publishing.

The hero monogram is used because no portrait was provided. The project thumbnail is explicitly an illustrative sketch, not a screenshot. Replace either only with an approved portrait or a real project image, and update its accessible text accordingly. No CV, project repository/demo URL, verified Oracle certificate, testimonials, or articles were provided, so the site does not invent or link to them.

The DEPI entry is labeled as training and does not imply completion; its status was not specified. Verify the Event Management System's final implementation before publishing the listed technology stack. The contact form uses `mailto:` and opens the visitor's email application; it does not deliver or store messages itself. To send messages directly from the site, connect a trusted form endpoint and add server-side validation and spam controls.

Before launch, replace `https://example.com/` in `index.html`, `public/robots.txt`, and `public/sitemap.xml` with the deployed canonical domain. If the hosting provider requires a raster social card, replace the `og:image` URL with a PNG or JPEG version of `public/og-image.svg`.
