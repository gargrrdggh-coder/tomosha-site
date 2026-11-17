# Tomosha, My Whole World

A one-page love letter site, made as a gift. It is a single self-contained `index.html`.
Photos, fonts fallback and the song are all embedded, so nothing else needs to be hosted.

## What is inside

- Envelope with a draggable ribbon and bow
- Six truths, reasons counter, memory lights with photo lightbox
- Scratch coupons and "open when" notes
- A greeting card that opens in 3D, with a cassette that plays the song
- A gift box: pull the ribbon to reveal the rose photo
- A final question with a shy "No" button

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site (about 6 MB) |
| `vercel.json` | Clean URLs, always-fresh cache, no search indexing |
| `README.md` | This file |

## Run locally

Open `index.html` in a browser. No build step.

## Deploy on Vercel

1. Push this folder to GitHub.
2. On vercel.com choose Add New, then Project, and import the repo.
3. Framework Preset: Other. Leave build command and output directory empty.
4. Deploy.

Or with the CLI: `npm i -g vercel`, then run `vercel --prod` in this folder.

## Notes

- The song starts when the card is opened (browsers require a tap first).
- Fonts load from Google Fonts. Without internet, serif/cursive fallbacks are used.
- Keep this repo private if you do not want the page to be public.
