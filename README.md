# Leonida Trophy Index

Offline guide and tracker for all 55 PlayStation 5 trophies in Grand Theft Auto VI.

Open `app/index.html` in a desktop browser. Everything is local: the trophy list lives in `app/data/trophies.json`, progress is saved in the browser, and no network request is made.

## What is in the app

- All 55 official trophy names, descriptions and grades, plus a guide in this entry's own words for each one
- Source line beside every guide, drawn from the official PlayStation trophy text and public trophy references
- Platinum roadmap built from the official description stages
- Missable flags for story missions, choices, collectible sweeps and counted activities
- Checklist with grade and kind filters, search, spoiler mode, progress bar, export and import
- Four real screenshots in `screenshots/`, taken from the app running in a browser

## Files

- `app/index.html`, `app/style.css`, `app/app.js`, `app/data/trophies.json` — the whole app
- `main.ts` — copies `app/` and `screenshots/` to the output directory and writes `dossier.json` with the kit's vendored library
- `vendor/makefun-frontend.ts` — kit copy, left unchanged

No Rockstar Games logo, official artwork or game screenshot is used. This is a fan-made guide with original layout and original guide text.
