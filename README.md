# UNFOOD Landing Page

Official landing page for **UNFOOD** — the agentic smart wearable companion for zero-effort healthy living.

## Live

After connecting this repo to Cloudflare Pages the site will be available at:

`https://unfood-lp.pages.dev`  
(or your custom domain)

## Local preview

```bash
npx serve .
# or just open index.html in a browser
```

## Deploy to Cloudflare Pages (one-time)

1. Go to [Cloudflare Dashboard → Pages](https://dash.cloudflare.com/?to=/:account/pages)
2. **Create a project** → **Connect to Git**
3. Select the repository `sree-pm/unfood-lp`
4. Build settings:
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`  (or leave default)
5. Click **Save and Deploy**

Cloudflare will automatically redeploy on every push to `main`.

## Features

- 12 carefully designed sections
- Fully responsive + mobile-first
- WCAG-friendly structure & reduced-motion support
- Cinematic dark theme with ambient gradients
- Real product photography embedded
- Scroll-triggered fade-up motion
- Working waitlist form UI (backend can be wired later)
- Premium Tesla-inspired design language

## Project structure

```
index.html   ← complete single-file landing page (images embedded)
README.md
```

Built with vanilla HTML/CSS/JS. No build step required.
