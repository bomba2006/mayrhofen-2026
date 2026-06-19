# Mayrhofen / Zillertal 2026 — Research Project

Hiking research for 3 adults, Aug 31 – Sep 8, 2026. Self-catering basecamp in Mayrhofen, Austrian Alps.

## Deploy to Vercel

1. Push this repo to GitHub
2. Import to Vercel — auto-detects static site
3. Or: `vercel` CLI from project root

## Files

- `public/index.html` — Mobile-first dashboard with all data + ZIP download
- `public/mayrhofen-zillertal-2026-report.html` — Full research report (warm theme)
- `public/mayrhofen-zillertal-2026-linear.html` — Full report (Linear dark theme)
- `public/mayrhofen-zillertal-2026-map.html` — Interactive trail map with elevation profiles
- `public/mayrhofen-zillertal-2026-mobile.html` — Mobile-optimized dashboard
- `public/notes-data.json` — All hike/drive/weather/accommodation data
- `public/notes-data.js` — Same data as JS for browser use

## Data Included

- 12 hikes ranked by steepness (gain/km)
- 3 scenic drives
- 5 day-by-day itinerary plans
- Per-hike weather with altitude temps
- Accommodation, supermarkets, restaurants
- Strudel & coffee directory
- Activcard pricing analysis
- Cable car 2026 season dates
- Salzburg 2025 reference data

## Tech

Static HTML + CSS + vanilla JS. Leaflet for maps. JSZip for downloads. Zero build step.
