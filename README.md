# KW Resume Site

Personal resume and portfolio for Kevin Wang, deployed at https://kcwang.cyou.

- `/` — Card / visual resume
- `/console/` — Developer console resume
- `/portfolio/` — Portfolio index
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
