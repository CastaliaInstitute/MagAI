# MagAI — Castalia Institute

Public recruitment site for the Castalia Institute online MagAI certificate.

The site is deployed to GitHub Pages at `https://magai.castalia.institute/`.
Detailed course books remain canonical on the Magisterium site:

- https://magisterium.castalia.institute/magai/marketing/
- https://magisterium.castalia.institute/magai/science/

## Local preview

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

## DNS

Create this Cloudflare DNS record after GitHub Pages is enabled:

```text
Type: CNAME
Name: magai
Target: castaliainstitute.github.io
Proxy status: DNS only
```

Then set `magai.castalia.institute` as the custom domain in this repository’s Pages settings and enforce HTTPS.

The credential is proprietary and certificate-based; it is not an accredited academic degree or professional license.
