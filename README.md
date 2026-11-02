# AOUN Website — MVP

An archived AOUN website prototype built with React, Vite, Tailwind CSS, GSAP, and Framer Motion.

## Repository
https://github.com/bureaufaiez/proj-260507-aoun-website

## Cloudflare Pages — setup

- **Status:** Not yet confirmed as deployed to Cloudflare Pages (2026-11-02).
- **Suggested Cloudflare account:** BUREAU FAIÈZ
- **Suggested Pages project name:** `proj-260507-aoun-website`
- **Potential default URL (unverified):** https://proj-260507-aoun-website.pages.dev/
- **Framework:** React (Vite)
- **Production branch:** `main`
- **Build command:** `npm run build`
- **Build output directory:** `dist`
- **Root directory:** Repository root (leave blank)
- **Custom domain:** Not needed

The exact `pages.dev` URL must be recorded after deployment. Do not treat the URL above as live until Cloudflare confirms it.

## Workflow — DEV → PREVIEW → LIVE

1. **DEV:** Implement on `feature/*` or `codex/*` branches; integrate into `dev`.
2. **PREVIEW:** Promote `dev` into `preview` for Cloudflare branch-preview QA.
3. **LIVE:** Promote `preview` into `main` only after approval; Cloudflare deploys production automatically.

On Cloudflare Pages, set the production branch to `main`. Under **Settings → Builds → Branch control**, allow `preview` as the only automatic preview branch when available.

Existing `codex/*` branches are preserved. The website code on `main` has not been modified as part of this setup.

## No local installation required

The repository is ready for Git-based build configuration. The owner can connect it from Cloudflare's browser dashboard without terminal commands. Cloudflare handles dependency installation and compilation.

## Notes

- This is an archived/experimental AOUN project and should not be confused with the current BUREAU FAIÈZ website.
- Verify all runtime assets, external resources and animations after the first successful Pages build.
