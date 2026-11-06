# Alyasmina Hamed — Portfolio

Bilingual (English / العربية) one-page portfolio website. Static HTML, no build step.

## Structure
```
index.html      the whole site (HTML + CSS + JS)
img/            all images (WebP + PNG portrait, favicon, social preview)
.nojekyll       tells GitHub Pages to serve files as-is
```

## Publish on GitHub Pages
1. Create a new repository (e.g. `alyasmina-portfolio`) and upload everything in this folder (keep the `img` folder next to `index.html`).
2. Repository → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
3. After about a minute the site is live at `https://<your-username>.github.io/alyasmina-portfolio/`.

## Publish on Netlify / Vercel / any hosting
- **Netlify:** drag this folder onto https://app.netlify.com/drop
- **Vercel:** import the GitHub repo, framework preset *Other*, no build command.
- **cPanel / shared hosting:** upload the folder contents into `public_html`.

## Language
- Opens in the visitor's browser language; the button in the top bar switches EN ⇄ AR.
- Direct links: add `#ar` or `#en` to the URL (e.g. `…/index.html#ar`).

## Editing
- Every text exists twice: `<span class="en">…</span><span class="ar">…</span>`. Edit both.
- Colours and fonts are CSS variables at the top of `<style>` in `index.html`.
- To add a design: put the image in `img/` (WebP, ~900px wide) and reference it as `img/name.webp`.
