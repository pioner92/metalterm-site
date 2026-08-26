# Metalterm

Metalterm is a fast, GPU-rendered terminal for macOS, built on Metal 3.

[![Sponsor](https://img.shields.io/badge/Sponsor-30363D?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/pioner92)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/pioner92)

![Metalterm demo](assets/demo.gif)

## About this repository

This is Metalterm's public home for the website, releases, bug reports, and feature
requests. The application source code is private and is not hosted in this repository.

## Download

Download the latest notarized macOS release from [metalterm.dev](https://metalterm.dev).

## Feedback and support

- Report reproducible problems in [Issues](https://github.com/pioner92/metalterm-site/issues/new).
- Share ideas and feature requests in [Issues](https://github.com/pioner92/metalterm-site/issues/new).
- For private support, email [support@metalterm.dev](mailto:support@metalterm.dev).

When reporting a problem, please include your Metalterm version, macOS version, and steps to reproduce it.

## Releases

Downloads and release notes are available on the [Releases](https://github.com/pioner92/metalterm-site/releases) page.

## Contributing

Website fixes and documentation improvements are welcome. Changes to the Metalterm application itself cannot be contributed here because its source code is private.

## Website maintenance

The repository contains a single static page (`index.html`) served by GitHub Pages at
[metalterm.dev](https://metalterm.dev), along with its icons and manifest in `assets/`.

### Local preview

```
python3 -m http.server 8000
```

then open `http://localhost:8000`.

GitHub Pages deploys from the `main` branch at the repository root. The `CNAME` file configures the `metalterm.dev` domain.
