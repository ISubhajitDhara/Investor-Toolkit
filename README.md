# Investor Toolkit — GitHub Pages website + bilingual learning app

A responsive English + Bengali personal-finance education website. The home page includes the interactive learning app; separate article pages are provided for search engines and sharing.

## Included
- Existing bilingual interactive learning app (lessons, quizzes, filters, saved/completed progress)
- SEO-friendly guide pages: SIP, mutual funds, term insurance, emergency fund and credit score
- Learning hub, About, Privacy Policy and Educational Disclaimer pages
- `robots.txt`, `sitemap.xml`, web manifest and SVG app icon
- Mobile responsive layout; no backend or paid hosting required

## Publish with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `investor-toolkit` (or another name you prefer).
2. Upload the complete contents of this folder to the repository root. Keep `index.html`, `app.js` and `styles.css` at the root; do not upload only the ZIP file.
3. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for the Pages deployment to finish. Your site URL will appear in Settings → Pages.
6. Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` in `sitemap.xml` and `robots.txt` with the actual Pages URL, then commit the changes.
7. Open the website URL and test all navigation, articles, language switching, quizzes and mobile layout.
8. Add the sitemap URL in Google Search Console and request indexing for the homepage and key article pages. Indexing and ranking are not guaranteed.

## Project files
- `index.html`, `styles.css`, `app.js`: interactive learning app and home page
- `seo.css`: styles for article and SEO sections
- `articles/`: standalone search-friendly guides
- `learn/index.html`: article directory
- `about.html`, `privacy.html`, `disclaimer.html`: supporting pages
- `sitemap.xml`, `robots.txt`: search crawler files (customize URL after deployment)
- `site.webmanifest`, `assets/icon.svg`: installable-site metadata and icon

## Important before public launch
- The Privacy Policy is a starter template. Update it to match any analytics, advertising, forms, payment services, app SDKs or other tools actually enabled.
- The financial articles are general educational drafts, not personalised advice. Review facts and product/regulatory references against current official sources before publishing.
- Add a real contact channel and publisher details if appropriate. Do not add fake testimonials, performance claims or guaranteed-return language.
- The app currently stores progress only in the visitor's browser. There is no account system, cloud sync, CMS, payment system or server.
- No Google Play download link is shown yet because the Android app has not been published. Add the official Play Store URL only after approval.

## Local preview
Open `index.html` in a browser. For testing relative links and the service-worker-free static site, a local static server is also suitable.
