# Metalterm

The landing page for [Metalterm](https://metalterm.dev) — a GPU-rendered macOS terminal built on Metal 3.

![Metalterm demo](assets/demo.gif)

## What's here

A single static page (`index.html`, no build step) served by GitHub Pages at
[metalterm.dev](https://metalterm.dev), plus the icons and manifest in `assets/`.

## Local preview

```
python3 -m http.server 8000
```

then open `http://localhost:8000`.

## Deployment

GitHub Pages, source = `main` branch, root. The custom domain is set via `CNAME`
(`metalterm.dev`), with Cloudflare DNS pointed at GitHub Pages' IPs.

## Releases

Every build is published in two places from the Metalterm release script:

- [`downloads`](https://github.com/pioner92/metalterm-site/releases/tag/downloads) is the
  permanent asset container used by the Sparkle appcast at
  `https://metalterm.dev/appcast.xml`;
- `vVERSION` is the human-facing release with notes, the same notarized `.dmg`, and the
  Latest badge. The website's download button points at this versioned asset.

The duplicated assets intentionally serve different stable URLs. The release script checks
that both GitHub SHA-256 digests match before publishing the site and appcast.

## Support

support@metalterm.dev
