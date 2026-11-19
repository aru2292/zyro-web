# ZYRO website ( Pages)

Files: `index.html` (landing page), `privacy.html` (privacy policy). No build step, no paid service, no external libraries.

## Put it online for free (GitHub Pages)
1. Create a **public** GitHub repo, e.g. `zyro-site`.
2. Upload `index.html`, `privacy.html`, `README.md` to the repo root (Add file → Upload files → Commit).
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
4. After ~1 minute the site is at `https://<your-username>.github.io/zyro-site/`.

## Free custom domain (optional)
- **Free subdomain:** `is-a.dev` or similar free-subdomain services accept a GitHub pull request. Point the subdomain to `<your-username>.github.io`.
- **Own domain:** buy a cheap domain, then in Settings → Pages set **Custom domain**, and add the DNS records GitHub shows you.
- Free domain offers change; check the current terms before signing up.

## Before you publish
- Replace the placeholder support/invite links if they change.
- Set real premium prices in the "Premium" section (currently "Ask").
- The privacy page is the same policy as `PRIVACY_POLICY.md` in the bot repo; keep both in sync.
