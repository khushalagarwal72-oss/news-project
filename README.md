# Hindusthan Time

A React + Vite news homepage.

## Run locally

```bash
npm install
npm run dev
```

Open the printed local URL (usually http://localhost:5173).

## Build for production

```bash
npm run build
npm run preview
```

`npm run build` outputs a static site into the `dist/` folder — this is what you deploy.

## Get a live URL (free, ~2 minutes, no account needed to try)

**Option A — Netlify Drop (fastest)**
1. Run `npm run build` to create the `dist/` folder.
2. Go to https://app.netlify.com/drop
3. Drag the `dist/` folder onto the page.
4. Netlify gives you a live `https://your-site.netlify.app` URL instantly.

**Option B — Vercel**
1. Push this folder to a GitHub repo.
2. Go to https://vercel.com/new and import the repo.
3. Vercel auto-detects Vite — click Deploy.
4. You get a live `https://your-site.vercel.app` URL.

**Option C — GitHub Pages**
1. Push this folder to a GitHub repo.
2. Add `base: '/your-repo-name/'` to `vite.config.js`.
3. Run `npm run build`, then deploy the `dist/` folder using the `gh-pages` package or GitHub Actions.
