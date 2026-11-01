# Catalin Dragusanu — Portfolio

Personal portfolio site built with [Astro](https://astro.build) and Tailwind CSS, deployed to Netlify.

**Live site:** https://portfoliocatalindragusqanu.netlify.app

## Development

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # static output in dist/
npm test         # markdown lint
```

## Content

Projects, blog posts, experience and skills live in `src/content/` as markdown and JSON files:

```text
src/content/
  projects/
  posts/
  experience/
  skills/
```

Pages, components and layouts are in `src/pages/`, `src/components/` and `src/layouts/`.

## Configuration

Copy `.env.example` to `.env` to override the name, role, tagline, contact details, social usernames, resume link and analytics (Google Analytics, Plausible or Umami). Every variable is documented in `.env.example`.

## Deployment

Pushes to `main` build and deploy via GitHub Actions (`.github/workflows/site.yml`).

| Secret | Required |
| --- | --- |
| `NETLIFY_AUTH_TOKEN` | Yes |
| `NETLIFY_SITE_ID` | Yes |
| `SLACK_WEBHOOK_URL` | No (deploy notifications) |
