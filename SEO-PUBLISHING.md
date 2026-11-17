# ProudlyPH SEO publishing

The animated homepage and moving ticker remain intact. The directory contains 25 existing entries; 10 with substantive descriptions now have standalone searchable profiles.

## Content workflow
The public manifest is `data/catalog.json`. The fields `published` and `profile` control what `node tools/build-profiles.mjs` generates. The GitHub Action regenerates static profiles and sitemap when this manifest changes. The original moving ticker is still static: adding/removing entries must also update `ticker.html`; the manifest alone does not manage ticker inclusion. Before changing `published`, verify any associated ticker links. Do not put private information in this public repository.

## Google Sheets integration
A private Google Sheets Yes/No administration sync is **not enabled** by this release. It will require a verified spreadsheet, an authenticated integration and review of publishing controls. Do not publish a private admin sheet just to expose it to GitHub Pages.

## Social preview
The previously approved ProudlyPH PNG exists outside the repository. Its image metadata will be linked only once the exact approved asset is hosted publicly and has a verified HTTPS URL. Current social title and description metadata are preserved, with no broken image URLs.

## Search Console
Sitemap includes 12 URLs. Submission and discovery do not guarantee Google indexing. Inspect relevant new product URLs after deployment.
