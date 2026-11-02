# AOUN Website — MVP

An archived AOUN website prototype built with React, Vite, Tailwind CSS, GSAP, and Framer Motion.

## Repository
https://github.com/bureaufaiez/proj-260507-aoun-website

## Cloudflare Pages — setup

- **Status:** Deployed to Cloudflare Pages; owner confirmed successful publication (2026-11-02).
- **Suggested Cloudflare account:** BUREAU FAIÈZ
- **Suggested Pages project name:** `proj-260507-aoun-website`
- **Live URL:** https://proj-260507-aoun-website.pages.dev/
- **Framework:** React (Vite)
- **Production branch:** `main`
- **Build command:** `npm run build`
- **Build output directory:** `dist`
- **Root directory:** Repository root (leave blank)
- **Custom domain:** Not needed

The live URL above was supplied and confirmed by the project owner.

## Workflow — DEV → PREVIEW → LIVE

1. **DEV:** Implement on `feature/*` or `codex/*` branches; integrate into `dev`.
2. **PREVIEW:** Promote `dev` into `preview` for Cloudflare branch-preview QA.
3. **LIVE:** Promote `preview` into `main` only after approval; Cloudflare deploys production automatically.

On Cloudflare Pages, set the production branch to `main`. Under **Settings → Builds → Branch control**, allow `preview` as the only automatic preview branch when available.

Existing `codex/*` branches are preserved. The website code on `main` has not been modified as part of this setup.

## Initial deployment notes

- Initial Cloudflare Pages build failed with a syntax error in `src/App.jsx` at line 480.
- Fixed the malformed page-transition effect and undefined animation references on `dev`, then promoted through `preview` to `main` (PR #10 and #11, commit `f701224`).
- Owner subsequently confirmed successful deployment at the live URL above.

## No local installation required

The repository is ready for Git-based build configuration. The owner can connect it from Cloudflare's browser dashboard without terminal commands. Cloudflare handles dependency installation and compilation.

## Notes

- This is an archived/experimental AOUN project and should not be confused with the current BUREAU FAIÈZ website.
- Verify all runtime assets, external resources and animations after the first successful Pages build.
