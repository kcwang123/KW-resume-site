# KW Resume Site

Two resume presentations, one shared data layer.

- `/` — Card / Visual resume
- `/console/` — Developer Console resume
- `/portfolio/` — portfolio index
- `/projects/*` — case study routes

## Shared data

- `src/data/resume.json`
- `src/data/projects.json`
- `src/data/systems.json`

The current content is intentionally incomplete until the next resume / project / systems grill.

## Local development

```bash
npm install
npm run dev
```

## GitHub Pages

Deploys from `main` with `.github/workflows/deploy-pages.yml`.
