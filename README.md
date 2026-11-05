# Graphyzo

Graphyzo turns any table into the right chart. Upload or paste your data, pick from 115+ visualization techniques, style every element and export for web, print or publication.

Everything runs in the browser. The whole tool is one self-contained file, `index.html`. `og.jpg` is the image shown when the link is shared.

## Publishing

Cloudflare Workers is connected to this repository (Workers Builds): every change pushed to `main` is published automatically. `wrangler.jsonc` tells Cloudflare to serve the files here as a static site; `.assetsignore` keeps the repository's own files out of it.
