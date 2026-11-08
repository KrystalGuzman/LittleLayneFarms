# Little Layne Farms

Static, responsive website for Little Layne Farms, a K–4 farm and nature enrichment program in Escondido, California. The site has no build step or third-party runtime scripts.

## Preview

Open `index.html` in a browser, or serve this directory with any static HTTP server. Do not deploy the site over plain HTTP; production should use HTTPS.

## Before launch

1. Choose and verify the production domain with Nicole. Replace every `YOUR-PRODUCTION-DOMAIN` in `robots.txt` and `sitemap.xml` with that exact host. Add absolute canonical, Open Graph URL, and Open Graph image metadata to `index.html` once the domain is known.
2. Confirm current December session dates and availability, the two session schedules and $500 price, multi-day discount details, and the business contact information.
3. Confirm the privacy notice in `privacy.html` against the selected host's logging, retention, and security practices. Keep HTTPS enabled. The site currently has no forms, analytics, advertising, or tracking scripts.
4. Have Nicole provide and approve the actual enrollment terms before publishing them: cancellation and refund policy, animal interaction and farm safety rules, emergency procedures, required parent or guardian permissions, and photography or media consent. These terms are intentionally not invented here.
5. Have the business owner or qualified counsel review applicable federal and California privacy, child-safety, business, and accessibility obligations, including whether COPPA or California privacy laws apply to the actual enrollment process. Do not treat this informational site as a compliance determination.
6. Manually test keyboard navigation, focus visibility, mobile menu behavior, text resizing, contrast, screen-reader announcements, and reduced-motion behavior on mobile and desktop. Automated checks are not a WCAG conformance audit.
7. Validate the JSON-LD with Google's Rich Results Test or Schema.org Validator after deployment, then check the sitemap, robots file, HTTPS, and all page links on the production domain.

## Publishing

Publish the contents of this folder on a static hosting provider that supplies HTTPS. Configure the chosen custom domain at the host and registrar using that provider's current DNS instructions; the required record types and values vary by provider. After DNS and HTTPS are active, update the domain placeholders and add canonical/social URL metadata, then submit `/sitemap.xml` in Google Search Console and Bing Webmaster Tools.

No exact farm street address is published. Parents and guardians should contact Nicole directly for location and current enrollment details.