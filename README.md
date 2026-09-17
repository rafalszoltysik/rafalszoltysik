# Rafał Szołtysik

I build software, integrations and automation around real business problems.

This repository is the source for [rafalszoltysik.pl](https://rafalszoltysik.pl): personal site, project showcase, and professional hub.

## Focus

- E-commerce implementation and business process work
- Integrations, APIs, webhooks, automation
- Independent products (for example Squimbo and PlayGrid)
- Software and systems around real constraints, not demos for their own sake

Currently Implementation Specialist at Base Polska. Studying Computer Science (B.Eng.) at WSB Merito Chorzów.

## Links

- Site: [rafalszoltysik.pl](https://rafalszoltysik.pl)
- GitHub: [github.com/rafalszoltysik](https://github.com/rafalszoltysik)
- LinkedIn: [linkedin.com/in/rafał-szołtysik-a6064824a](https://www.linkedin.com/in/rafa%C5%82-szo%C5%82tysik-a6064824a)
- Email: [rafal.szoltysik1@gmail.com](mailto:rafal.szoltysik1@gmail.com)

## Stack

- Next.js (App Router), React, TypeScript
- CSS modules and design tokens in `app/globals.css`
- Typed local content in `content/`
- No CMS, database, auth, or analytics in the MVP

## Run

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Build

```bash
npm run lint
npm run typecheck
npm run build
npm start
```

Set `NEXT_PUBLIC_SITE_URL` before production (see `.env.example`).

## Content

Visitor-facing facts live in `content/`. Edit copy and projects there, not in components.

- `content/site.ts` - name, domain, tagline
- `content/profile.ts` - role, education, tools
- `content/projects.ts` - case studies
- `content/copy.ts` - page copy
- `content/social.ts` - links (only `confirmed: true` entries render)

Do not invent URLs, metrics, or screenshots.
