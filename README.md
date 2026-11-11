# CBPayments Blog

Public static website: https://blog.cbpayments.cc/

Repository: https://github.com/cbpayments/cbpayments-blog  
Publishing: GitHub Pages from the `main` branch, repository root.  
Custom domain: `blog.cbpayments.cc`.

## Site structure

- `index.html` — homepage
- `blog/index.html` — article archive
- `blog/<slug>/index.html` — individual article pages
- `about/index.html` — publication information
- `editorial-policy/index.html` — editorial and review standards
- `disclaimer/index.html` — general information disclaimer
- `assets/style.css` — shared responsive styles
- `robots.txt` — crawler guidance
- `sitemap.xml` — canonical public URLs
- `templates/article-template.html` — reusable article starter

## Human-reviewed publishing workflow

1. Draft the article and SEO metadata.
2. Send the complete draft and proposed URL to the site owner for review.
3. Do not publish a draft until the owner explicitly approves it.
4. After approval, add `blog/<slug>/index.html`.
5. Update the article archive at `blog/index.html` and homepage feature if appropriate.
6. Add the canonical article URL and last-modified date to `sitemap.xml`.
7. Check the deployed URL, canonical tag, page title, meta description, structured data and internal links.
8. Submit the sitemap in Google Search Console when needed.

## SEO conventions

- Use one descriptive H1 per page.
- Give every indexable page a unique title, meta description and self-referencing canonical URL.
- Use absolute HTTPS URLs in canonical tags, Open Graph URLs, JSON-LD and sitemap entries.
- Use descriptive internal-link text and useful image alternative text.
- Do not add fabricated reviews, author credentials, statistics, regulatory claims or product promises.
- Keep educational content distinct from product claims and include relevant risk/context disclosures.
- Do not claim that sitemap submission guarantees indexing or rankings.

## Deployment notes

GitHub Pages automatically builds from the configured branch and root directory. Changes committed to `main` trigger a deployment. Preserve `CNAME` and do not change the custom domain or DNS settings as part of routine content publishing.
