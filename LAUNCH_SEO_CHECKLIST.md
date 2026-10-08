# HMG launch / SEO checklist

The GitHub Pages preview is intentionally **noindex** and robots.txt disallows crawling.

## Immediately before publishing heflinmedia.com
1. Connect and test the Airtable contact form, acknowledgment, and follow-up workflow.
2. Confirm custom domain, DNS, HTTPS, and internal links from Wynncrest.
3. Remove `<meta name="robots" content="noindex,nofollow">` from **all six HTML pages** (or replace with `index,follow,max-image-preview:large`).
4. Change `robots.txt` to:

   User-agent: *
   Allow: /
   Sitemap: https://heflinmedia.com/sitemap.xml

5. Update `assets/js/site.js` if any content changes are made; the same site copy appears in rendered static HTML and JS. Prefer one publishing pipeline long-term.
6. Verify each rendered page has one correct H1, title, canonical link, and Organization/Service JSON-LD.
7. Test mobile navigation, forms, redirects from the old HMG site, accessibility, and Google Search Console.
8. Submit https://heflinmedia.com/sitemap.xml in Search Console after launch.

**Important:** Publishing now without removing the staging directives can cause the new site to be excluded from search results. Do not remove them while still using the temporary preview.
