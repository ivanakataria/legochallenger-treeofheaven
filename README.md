# Tree of Heaven Tracker

A **treatment companion** to [iNaturalist](https://www.inaturalist.org/) for invasive *Ailanthus altissima* (Tree of Heaven) management.

Open `tree-of-heaven-tracker.html` in a browser (no build step). Data stays in `localStorage` on that device.

## What this tool is (and isn’t)

| Do this here | Do this on iNaturalist / Seek |
| --- | --- |
| Track treatment status & clearance | Species identification |
| Scientist / field validation requests | Biodiversity observations |
| 5-year treatment forecasts | Community photo ID |
| Import selected iNat observations into a local treatment log | Recording new wild sightings |

This app is **not** a competing ID or observation platform. Use [iNaturalist](https://www.inaturalist.org/taxa/57278-Ailanthus-altissima) or [Seek](https://www.inaturalist.org/pages/seek_app) to identify and record Tree of Heaven, then pull those spots here when you’re ready to manage invasive treatment.

## Features

- **iNaturalist panel** — links to the taxon page (`taxon_id=57278`), observe/upload, browse, and Seek; live fetch of nearby observations via the public API (`lat`/`lng`/`radius` or US state `place_id`).
- **Import** — add selected observations into the local treatment tracker with iNat id/uri; skips duplicates; research-grade marks validation as confirmed while treatment status stays “not treated” until you update it.
- **Field quick-check** — short checklist + reference photos; confirmation still points to iNaturalist/Seek.
- **Scientist network & requests** — sample directory, QR field tags, request/report workflow.
- **Charts & forecast** — concentration by state, treatment breakdown, drone + fungus 5-year model.
- **CSV export/import** and admin reminders / stalled follow-up / invalid-tree cleanup.

## Quick start

1. Open `tree-of-heaven-tracker.html`.
2. On **Track & Treat**, use the iNaturalist panel: pick a state or allow location, fetch observations, **Import** ones you want to treat.
3. Switch to **Scientists & Treatment** to request visits and log reports.
4. Use **Overview & Summary** for charts and the 5-year forecast.

See `tree-of-heaven-tracker-prompts.md` for section-by-section product copy notes.
