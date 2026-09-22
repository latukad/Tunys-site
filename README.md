# TUNYS KI Studio public site

Static GitHub Pages site for the TUNYS KI Studio OAuth/Google-facing public homepage.

## Included
- `index.html` — public homepage
- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `styles.css` — responsive black/orange design
- `.nojekyll` — serve files directly

## Publish now on GitHub Pages
1. Create a **public** GitHub repository, for example `tunys-site`.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`.
6. Save and wait for the `github.io` address to appear.

## Later, after tunys.eu.org is approved
1. In GitHub **Settings → Pages**, set custom domain to `tunys.eu.org` first.
2. Then add the DNS records requested by GitHub in deSEC.
3. Enable **Enforce HTTPS** when GitHub allows it.
4. Verify `tunys.eu.org` in Google Search Console.
5. Use these OAuth branding URLs:
   - Homepage: `https://tunys.eu.org/`
   - Privacy: `https://tunys.eu.org/privacy.html`
   - Terms: `https://tunys.eu.org/terms.html`

## Important
Before submitting Google verification, confirm every statement in the privacy policy still matches the actual TUNYS implementation.
Do not put OAuth tokens, client secrets, API keys, logs, or other credentials in this public repository.
