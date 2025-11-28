# Copilot Working Notes

## Overview & Architecture
- Single-page Vue 2 app built with Vue CLI 4; entry point is `src/main.js` mounting `App.vue` into `#app`.
- `App.vue` owns all UI (logo, copy, CTA links) and uses a simple `links` data array—no Vue Router, Vuex, or backend APIs.
- Static assets live in `public/`; they are referenced with absolute paths (e.g. `/currency-pound.svg`) so they are copied verbatim during builds.
- `staticwebapp.config.json` enables SPA-style navigation fallback for Azure Static Web Apps; keep it updated if routes are ever added.

## Local Dev & Tooling
- Install deps with `npm install`; run `npm run serve` for hot module reloading and `npm run build` to emit production assets into `dist/`.
- `npm run lint` runs the Vue/ESLint essential rule set; keep inline templates compliant with those defaults.
- `npm start` serves the prebuilt `dist/` via `serve -s dist`, useful for verifying the exact deploy bundle.
- Toolchain targets Node 16 (declared in `package.json` devDependencies); align local Node version to avoid CLI mismatches.

## Styling & Assets
- All styling lives inside `<style>` of `App.vue`; fonts pulled via Google Fonts import—avoid moving to external CSS unless you also update build config.
- Buttons use `.link1` plus nested `.link-content` and absolutely-positioned `.link-logo`. When adding new UI, reuse these classes to keep layout consistent.
- Iconography relies on CSS `mask-image` pointing to SVGs in `public/`; add new SVGs there and map them with a new `.logoX` class selector.

## Link Data Model
- `links` array items require `{ text, href, logoClass }`; `text` doubles as the Vue `:key`, so keep values unique.
- External URLs always open in a new tab via `target="_blank"`; include fully qualified URLs with protocol to avoid Azure Static Web Apps rewriting them.
- If adding campaign-specific copy blocks, keep accessibility text (`alt`, `<p>` copy) in sync and maintain the existing semantic structure for screen readers.

## Deployment & CI
- GitHub Action `.github/workflows/azure-static-web-apps-purple-cliff-02dd23f03.yml` builds on every push/PR to `main` using `Azure/static-web-apps-deploy@v1`.
- Workflow assumes `app_location: /`, `output_location: dist`, and an (absent) `api/` folder. If you add an API, place it in `/api` or update the workflow.
- Production hosting is Azure Static Web Apps; respect their build outputs (no server-side rendering). SPA fallback already set via `staticwebapp.config.json`.

## Conventions & Tips
- Keep `App.vue` declarative; prefer expanding the data array or computed helpers before introducing additional components.
- When adjusting typography/colors, do it within the existing CSS blocks to avoid duplicating style definitions across components.
- Use absolute imports for anything placed under `public/` (leading slash) and relative imports for `src/assets` so the Vue CLI asset pipeline processes them correctly.
- Before opening PRs, run `npm run lint && npm run build` so the Azure workflow mirrors a clean local state.
