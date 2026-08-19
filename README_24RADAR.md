# 24RADAR — 24SPY scale replica frontend

This build uses the official 24SPY repository's frontend structure, CSS, canvas map,
tiles, menus, settings, flight-plan UI, and controller UI as the visual/interaction
base. The live traffic/controller source is switched to the same-origin 24RADAR
`/api/live` endpoint.

- Keep `assets/` and `tiles/` alongside `index.html`.
- Keep the 24RADAR backend/API route that serves `/api/live`.
- The 24SPY external controller/update endpoints are not used by the live sync.
- Aircraft are rendered natively on the existing 24SPY canvas and remain clickable.
