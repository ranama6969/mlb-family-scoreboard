# Toronto Sports Scoreboard v6

v6 builds on v5 with three view modes:

- **Today** — existing live/upcoming game picker and full-screen scoreboard.
- **Yesterday** — completed games from the previous calendar day, cycling every 8 seconds.
- **Standings** — current league standings for MLB, NHL, or NBA.

The design remains intentionally passive: no news, videos, ads, betting, or scrolling feeds.

## Data

Scores, schedules, teams and standings are fetched client-side from ESPN's public-facing endpoints. These endpoints are not an official supported public API and may change without notice.

## GitHub Pages

Upload `index.html` to the root of a public GitHub repository and enable:

Settings → Pages → Deploy from branch → `main` → `/ (root)`

Then open the generated GitHub Pages URL on the tablet.

## Recommended family-room setup

1. Open the site.
2. Choose Today / Yesterday / Standings.
3. For a live game, select the game and tap FULL SCREEN.
4. On iPad, use Guided Access to keep the device in the scoreboard page.
