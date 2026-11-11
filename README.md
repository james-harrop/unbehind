# Unbehind

Landing page for [unbehind.ai](https://unbehind.ai) - AI set-up and care for owner-run firms and busy professionals.

## Stack

Static HTML. No build step. Hosted on Vercel.

## Local preview

Open `index.html` in any browser, or:

```sh
python3 -m http.server 8000
```

## Deploy

```sh
vercel --prod
```

## Assets

- `index.html` - the page (v14: set-up repositioning, Nov 2026)
- `index.v13.html` and earlier - previous versions, kept for reference
- `fonts/` - self-hosted Bricolage Grotesque and Newsreader (SIL Open Font License)
- `favicon.svg` - yellow tile, ink tick
- `apple-touch-icon.png` - 180×180
- `og.png` - 1200×630 social preview
- `og-generator.html` - template used to render `og.png` via Playwright

## Regenerating the OG image

```sh
node scripts/generate-og.mjs
```
