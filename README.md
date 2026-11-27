# Luanda Rodrigues Portfolio

Bilingual data portfolio built with **Astro** and deployed on **Vercel**.

- Live site: https://luandarodrigues-portfolio.vercel.app/
- GitHub profile: https://github.com/luandarod
- Languages: English at `/` and Portuguese at `/pt/`

## Highlights

- Health analytics, BI, SQL, cloud analytics and machine learning cases
- Live project pages and interactive analytical products
- English and Portuguese content
- Contact form routed through the Vercel API

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy

Import this GitHub repository into Vercel and use the default Astro settings. The production branch is `main`.

## Main structure

- `src/data/homeContent.ts`: bilingual portfolio content and project links
- `src/components/PortfolioHome.astro`: main portfolio interface
- `src/pages/`: English and Portuguese routes
- `public/dashboards/`: published analytical dashboards
- `api/contact.js`: contact-form endpoint
