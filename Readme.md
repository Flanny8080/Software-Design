# RightOnPar LLC — Site

A single-page landing site listing RightOnPar LLC's products: the web app, two companion sites, and the AI phone assistant.

## What's in here

- `index.html` — the whole site (HTML, CSS, and JS in one file, no build step)
- `robots.txt` — tells search engines they can crawl the site
- `sitemap.xml` — helps Google index the page

## 1. Fill in your real content

Open `index.html` and search for `EDIT ME`. You'll find four product blocks ("holes" on the scorecard) — replace for each one:

- The name in `<h3>[...]</h3>`
- The description in the `<p>`
- The `href="https://example.com"` with the real live URL

Also update:
- The `<meta name="description">`, Open Graph, and Twitter tags near the top with your real copy
- `https://www.rightonpar.com/` references (canonical URL, sitemap, structured data) — swap in your real domain
- The about section and contact email near the bottom

## 2. Put it on GitHub Pages

1. Create a new GitHub repo (e.g. `rightonpar-site`).
2. Push these files to the root of the `main` branch.
3. In the repo, go to **Settings → Pages**.
4. Under **Source**, choose `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a URL like `https://yourusername.github.io/rightonpar-site/`.

## 3. Point your real domain at it (optional)

If you own `rightonpar.com` (or similar):

1. In **Settings → Pages**, add your custom domain.
2. At your domain registrar, add a `CNAME` record pointing to `yourusername.github.io`, or `A` records pointing to GitHub's IPs (GitHub will show you the exact values once you add the custom domain).
3. Update every `rightonpar.com` reference in `index.html` to match your actual domain.

## 4. Basic SEO checklist

- [ ] Real meta description and title (already templated, just confirm wording)
- [ ] Real Open Graph image — add an `og-image.png` (1200×630px) to this folder and update the `og:image` URL
- [ ] Submit `sitemap.xml` in [Google Search Console](https://search.google.com/search-console) once the domain is live
- [ ] Each product link uses `rel="noopener"` already (good for security and doesn't hurt SEO)
- [ ] Add real alt text if you add any images later

## Customizing further

Colors, fonts, and layout live in the `<style>` block at the top of `index.html`. The CSS variables at the very top (`--fairway-deep`, `--sand`, etc.) control the whole palette if you want to adjust the look.
