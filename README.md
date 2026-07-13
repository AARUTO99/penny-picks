# Penny Picks — Budget Tech Buying Guides

A static site (no build step, no framework) ready to deploy for free and submit to Google AdSense.

## What's included

- `index.html` — homepage
- `about.html`, `contact.html`, `privacy-policy.html` — required pages for AdSense approval
- `guides/budget-laptops.html`, `guides/budget-earbuds.html`, `guides/budget-smartphones.html` — the actual content
- `style.css` — all styling (single shared stylesheet)
- `robots.txt`, `sitemap.xml` — basic SEO plumbing (update the placeholder domain in both once you have one)

## 1. Before you deploy — do these first

1. **Contact page**: open `contact.html` and replace the placeholder email with a real one you check.
2. **Privacy policy**: open `privacy-policy.html` — it's a starting template, not legal advice. Fill in the bracketed sections (especially if you add analytics or a contact form later), and consider a quick legal review.
3. **Domain in sitemap/robots**: replace `YOUR-DOMAIN-HERE` in `sitemap.xml` and `robots.txt` once you have a real URL.

## 2. Deploy for free — GitHub Pages (recommended)

1. Create a free GitHub account if you don't have one, and create a new **public** repository (e.g. `penny-picks`).
2. Upload all the files in this folder to the repository, keeping the `guides/` folder structure intact.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a live URL that looks like `https://yourusername.github.io/penny-picks/` within a minute or two.

Alternative free hosts that work the same way: **Netlify** (drag-and-drop the folder at netlify.com) or **Cloudflare Pages**. Both are one-click and free.

## 3. Custom domain (optional but recommended before AdSense)

A `.github.io` subdomain can get AdSense-approved, but a real domain looks more established to both readers and reviewers. A `.com` typically costs $10–15/year from a registrar like Namecheap or Google Domains. Once you have one:
- Point it at your host following their custom domain instructions (GitHub Pages, Netlify, and Cloudflare Pages all have a simple settings page for this).
- Update `sitemap.xml` and `robots.txt` with the real domain.

## 4. Add more content before applying to AdSense

Google reviews for **genuine, substantial content** — three guides is a starting point, not a finished site. Aim for at least 10–15 solid pages before applying. Good next guides in this niche: budget monitors, budget webcams, budget routers/mesh Wi-Fi, budget keyboards/mice, budget power banks.

## 5. Apply to AdSense

1. Go to adsense.google.com and sign up with the site's URL.
2. Google will ask you to place a verification snippet in the `<head>` of every page — there's a placeholder comment (`<!-- AdSense verification/script goes here -->`) at the top of `index.html` showing where it goes; add it to every page's `<head>` the same way.
3. Review typically takes anywhere from a few days to a few weeks. Approval isn't guaranteed — it depends on content quality/quantity, site navigation, and traffic.
4. Once approved, Google will give you ad unit code to paste into the `.ad-slot` divs already placed in each guide.

## Notes on realistic expectations

Earnings depend almost entirely on organic search traffic, and a new site typically takes months to rank. This is a long-term project, not a quick payout — budget your time accordingly and keep publishing genuinely useful guides.
