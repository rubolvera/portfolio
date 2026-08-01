# Ruben Olvera — Portfolio (static site)

Plain HTML/CSS, no build step. 7 pages: `index.html`, `about.html`, and 5 project case files.
Images are pulled directly from your existing Google-hosted photo URLs, so there's nothing to re-upload.

## Fastest way to get a live custom-domain URL

### Option A — Netlify (easiest, drag-and-drop)
1. Go to https://app.netlify.com/drop
2. Drag this whole `site` folder onto the page — it deploys instantly to a `*.netlify.app` URL.
3. In Netlify: **Site settings → Domain management → Add a custom domain**, enter your domain, and follow the DNS instructions (you'll add a couple of records at your registrar — Netlify walks you through it).
4. Netlify auto-issues a free HTTPS certificate once DNS points to it.

### Option B — GitHub Pages (free, a bit more setup)
1. Create a new GitHub repo (e.g. `rubenolvera-portfolio`), public.
2. Upload all files in this folder to the repo root.
3. Repo → **Settings → Pages** → Source: `main` branch, `/ (root)` folder → Save.
4. Your site is live at `https://<username>.github.io/<repo>/`.
5. To use your own domain: in the same Pages settings, add your custom domain under "Custom domain," then at your registrar add a `CNAME` record pointing your domain (or subdomain) to `<username>.github.io`.

## Buying the domain
Porkbun or Namecheap — search for your domain, checkout, then point it at whichever host you pick above per that host's instructions.

## Notes
- `mailto:rubolvera@gmail.com` links are used in place of the old Google Sites "Booking Page" — swap in a real scheduling link (Calendly, etc.) if you set one up.
- All page content, work history, and awards were pulled directly from your published Google Site (sites.google.com/view/rubenolvera).
