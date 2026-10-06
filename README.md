# Sun and Soul 2027 · San Diego Vitality Con

Event website for Sun and Soul 2027, San Diego's first frontier health and wellness event in La Jolla, presented by Ēnel Health.

## Structure

- `index.html`: the full site (HTML, CSS and JS in one file)
- `img/`: photos, track backgrounds, speaker portraits and the dome video

The page loads GSAP, ScrollTrigger and Lenis from public CDNs and the fonts from Google Fonts. There is no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy

Static hosting works as-is. On Vercel, import this repo with framework preset "Other" and no build command, or run `npx vercel --prod` from the repo root.

## Placeholders to fill before launch

Dates, venue, prices, keynote speaker, sign-up form endpoint and the partner logo row are marked `[TBA]` or are placeholders in `index.html`.
