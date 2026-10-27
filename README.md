# Overlap Map (CS 448B Assignment 3)

Dual-radius dynamic queries on the staff Santa Clara County restaurants map. The view zooms the northwest (Stanford–Mountain View) band of the staff Mercator basemap so the useful restaurants dominate the frame. Drag circles A and B, keep restaurants in the intersection, and filter by address, placard, rating, and inspection score.

**Course:** Stanford CS 448B Visualization, Fall 2026  
**Student:** Manasvini Kothari  
**Due:** Monday Oct 26, 2026 by 10:30am

## Run locally

```bash
npm install
npm run dev
```

Open the printed URL (default [http://127.0.0.1:43123](http://127.0.0.1:43123)).

```bash
npm run build
npm run preview
```

## Data

Staff files under `public/data/`:

- `sccRestaurantsSynth2026.csv`
- `sccRestaurantsMap2026.png`

Source: [CS 448B A3](https://magrawala.github.io/cs448b-fa26/a3.html)

## Stack

Vite, vanilla JavaScript, D3 v7.
