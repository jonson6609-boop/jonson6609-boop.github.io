# The Small Fix — starter blog

A ready-to-publish blog: 4 posts, About/Contact/Privacy/Terms pages, SEO tags,
JSON-LD schema, sitemap, robots.txt, and marked ad slots. No build tools —
just plain HTML/CSS. $0 to launch.

## 1. Put it on GitHub Pages (free, ~10 minutes)

1. Create a free GitHub account at github.com if you don't have one.
2. Create a new **public** repository, e.g. `the-small-fix`.
3. Upload every file in this folder to that repository (drag-and-drop
   works on github.com — click "Add file" → "Upload files").
4. In the repo, go to **Settings → Pages**.
5. Under "Build and deployment", set **Source: Deploy from a branch**,
   branch **main**, folder **/ (root)**. Save.
6. After ~1 minute your site is live at:
   `https://YOUR-USERNAME.github.io/the-small-fix/`

## 2. Replace the placeholder domain

Every file has `https://YOURDOMAIN.example` in a few `<meta>`/`<link>` tags
and in `sitemap.xml` / `robots.txt`. Find-and-replace it with your real
GitHub Pages URL (or a custom domain if you buy one later — not required).

## 3. Get indexed by Google (free)

1. Go to [Google Search Console](https://search.google.com/search-console),
   add your site as a URL-prefix property.
2. Verify ownership (Search Console gives you an HTML file or meta tag —
   add it the same way you added other files).
3. Submit `sitemap.xml` under **Sitemaps** in the left menu.
4. Use "Request indexing" on your homepage and each post URL.

## 4. Write more content before applying to AdSense

Google AdSense wants to see a real, useful site — most approvals need
roughly **15–25 solid posts** and a site that's been live a few weeks,
though there's no official fixed number. Reuse the post template
(`posts/five-minute-budget-check.html` is a good one to copy) and:
- Keep the same `<link rel="stylesheet" href="../css/style.css">` path.
- Update the `<title>`, meta description, canonical URL, and JSON-LD block.
- Add a new `<article class="card">` block to `index.html`'s post grid.
- Add the new URL to `sitemap.xml`.

Good, honest, original writing matters more than volume — AdSense reviewers
(and readers) can tell when content is thin or copied.

## 5. Apply for Google AdSense (free)

1. Go to [google.com/adsense](https://www.google.com/adsense) and sign up
   with the site's URL.
2. Paste the AdSense site-verification snippet Google gives you into the
   `<head>` of `index.html` (there's a commented-out line ready for it).
3. Once approved, Google gives you an `ads.txt` line — paste it into
   `ads.txt`, replacing the placeholder comment.
4. Replace each `<div class="ad-slot">...</div>` block with the actual
   AdSense ad unit code Google provides (auto ads or manual units both work).
5. Wait for review. If rejected, the email will say why (usually "low value
   content" or "not enough content") — add more posts and reapply.

## 6. Keep growing it

- Publish consistently (even one post a week beats a big batch then silence).
- Target real search intent: specific, practical questions people type into
  Google, matching this site's short/practical tone.
- Internally link new posts to older ones.
- Once you have some traffic history, you can look at free tools like
  Google Search Console and Analytics to see what's actually bringing readers in.

No paid tools, themes, or hosting are required for any of this.
