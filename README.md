# Gerlos 2026 — Zillertal Arena

8-day hiking trip. Base: Appart Bergleben Deluxe, Gerlos (1,250m). 3 adults, self-catering. Aug 31 – Sep 8, 2026.

## Now on TREK

This trip has been migrated to [TREK](https://github.com/mauriceboe/TREK) — a self-hosted collaborative travel planner.

**Access:** `https://cyberigal-2.tailea5d3b.ts.net/` (Tailscale tailnet only)

### What's in TREK

- 9-day itinerary with day titles and notes
- 25 places mapped: 13 hikes, 9 huts/cafes, 2 restaurants, 2 supermarkets
- Accommodation: Appart Bergleben Deluxe (private sauna!)
- Budget: 11 items (~2,583 EUR)
- Packing list: 21 items

### Features

TREK provides:
- Interactive map with all locations
- Drag-and-drop day planning
- Budget tracking with EUR
- Packing checklist
- Weather forecasts (auto-fetched)
- PWA — install on phone, works offline
- PDF export for sharing
- Real-time collaboration (invite family)

## Legacy

The original static HTML research is preserved in `public/` and deployed on Vercel:
- `index.html` — Landing page
- `report.html` — Evidence dossier 
- `map.html` — Interactive trail map
- `companion.html` — Day companion

## Tech Stack

- **TREK:** Docker (`mauriceboe/trek:latest`), port 3000
- **Tailscale Serve:** HTTPS via tailnet
- **Research:** open-notebook (32 notes), gptr-mcp deep research
- **Sources:** outdooractive, bergfex, AllTrails, Komoot, Reddit, TripAdvisor
