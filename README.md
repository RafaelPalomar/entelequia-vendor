# entelequia-vendor

Release-only host for prebuilt bundles that entelequia Guix package
definitions fetch with `url-fetch` (the dotfiles repo is private, so its
release assets are not downloadable anonymously).  No code lives here.

| Tag | Asset | Consumer |
|---|---|---|
| `vendor-mmdc-<ver>` | `mmdc-bundle-<ver>.tar.gz` — `node_modules` for `@mermaid-js/mermaid-cli` + puppeteer, packed with `PUPPETEER_SKIP_DOWNLOAD=1` (no Chromium) | `entelequia/packages/mermaid-cli.scm` |
