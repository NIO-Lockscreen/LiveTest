# LiveTest

Static single-page tool (`index.html`) for testing the car lockscreen video layout. No build step.

## Deploy to Vercel

- **Dashboard:** import the repo at <https://vercel.com/new>. `vercel.json` sets Framework Preset to *Other* with no build/install command; nothing else to configure.
- **CLI:** `npx vercel` (preview) or `npx vercel --prod`.

Local preview: `npx vercel dev` or any static server (e.g. `python3 -m http.server`).

The old path `/video-layout-test(.html)` redirects to `/`.
