# Graphyzo

Graphyzo turns any table into the right chart. Upload or paste your data, pick from 115+ visualization techniques, style every element and export for web, print or publication.

Everything runs in the browser. The whole tool is one self-contained file, `index.html`. `og.jpg` is the image shown when the link is shared.

## Publishing

Every push to `main` is published to Cloudflare Pages at https://graphyzo.pages.dev/ by the GitHub workflow in `.github/workflows/publish.yml`. It needs two repository secrets, `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID`.
