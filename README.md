# KW Resume Site

Personal resume and portfolio for Kevin Wang, deployed at https://kcwang.cyou.

- `/` — Card / visual resume
- `/console/` — Developer console resume
- `/portfolio/` — Portfolio index
- `/consulting/` — Backend & systems consulting landing page (fractional / paid assessment)
- `/projects/*` — Case study routes

## Shared data

- `src/data/resume.json`
- `src/data/projects.json`
- `src/data/systems.json`

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

The static output is written to `dist/`. Production hosting is intended for Cloudflare Pages with the custom domain `kcwang.cyou`.

The consulting page links to the existing 30-minute Calendly endpoint. Confirm its live event type and availability before releasing. Do not add confidential client metrics or internal diagrams to the public page.
