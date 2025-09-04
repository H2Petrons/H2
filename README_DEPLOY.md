H2Petreon — 24/7 Hosting + Custom Domain (Zero $ hosting)
===========================================================

You have three free hosting choices. All run **24/7** and include TLS certificates.

Recommended: **Cloudflare Pages + Cloudflare DNS**
-----------------------------------------------
1) Create a Cloudflare account and add/register your domain **h2petreon.org** (transfer or register at cost price).
2) In Cloudflare → **Pages**, create a project and **Upload** this folder (no build step).
3) In Pages → **Custom domains**, add `www.h2petreon.org`.
   - Cloudflare will add a CNAME to your DNS automatically.
4) In **DNS → Records**, add a redirect from apex to `www` (Rules → Redirects → create rule `h2petreon.org` → 301 to `https://www.h2petreon.org/`). 
5) Wait 1–5 minutes for the certificate to issue. Your site is live worldwide.

Netlify (drag‑and‑drop) + Custom Domain
---------------------------------------
1) Go to https://app.netlify.com/drop and upload this folder.
2) Site appears at `https://<random>.netlify.app`.
3) In **Domain settings**, add custom domain `www.h2petreon.org`. Follow DNS instructions (usually a CNAME to `your-site.netlify.app`).
4) Add the apex redirect with `_redirects` (already included) or via Netlify UI.
5) TLS auto‑provisions.

GitHub Pages (from a branch) + Custom Domain
--------------------------------------------
1) Create a new public repo, add these files to the repo root.
2) Repo → Settings → Pages → Source: **Deploy from a branch** (branch `main`, root `/`).
3) Add custom domain `www.h2petreon.org` in Pages settings and commit the included `CNAME` file.
4) Point `www` via CNAME at `<your-username>.github.io`. For apex, use a redirect at your DNS provider to `https://www.h2petreon.org/`.
5) TLS auto‑provisions.

Monitoring (optional, free)
---------------------------
- Set up a free uptime monitor (e.g., UptimeRobot) to ping `https://www.h2petreon.org/` every 5 min.

Next steps
----------
- Replace the Donate / Discord / Open Collective links with your real URLs.
- Commit updates; Cloudflare/Netlify/GitHub redeploys automatically.
