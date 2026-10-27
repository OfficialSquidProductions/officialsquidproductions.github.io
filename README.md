# Squid Productions

A small, static software hub, built from the supplied website mockup. Each product name and icon links to its official website for information and downloads.

## Hosting

GitHub Pages serves the root of `main`. No build step, package install, JavaScript, analytics, or third-party font requests are needed.

Preview: https://officialsquidproductions.github.io/

To preview locally: `python3 -m http.server 8000` and open http://localhost:8000.

## Artwork and font

- `assets/squid-banner.png`: published Squid Productions banner from the Production Desk website.
- `assets/sp-green.png`: published Squid Productions monogram from the Shot Reporter repository. CSS uses its alpha mask for the four brand colors in the mockup.
- Pompiere by Karolina Lach: bundled locally under the SIL Open Font License, included in `assets/Pompiere-OFL.txt`.

Squid Productions names and artwork remain the property of their respective owner.

## Domain

The existing apex currently redirects through Squarespace to a Google Sites website at `www`. Connecting `squidproductions.org` requires a separate DNS cutover after verifying domain control. Preserve app subdomains, MX, SPF, and all unrelated records. No domain records are changed by this repository.
