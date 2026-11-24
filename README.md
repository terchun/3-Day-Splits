# 3-Day Full Body Tracker

A single-page workout tracker for a 3-day full-body split (Full Body A / B / C) with automatic progressive overload.

- **Setup:** enter starting weights (lbs), a default increment, and optionally a custom increment for each exercise.
- **Progression:** one cycle = Day 1 + Day 2 + Day 3. After every 2 completed cycles, each exercise's weight goes up by its increment.
- **Dashboard:** cycles completed, dates finished, calendar, per-exercise weight chart.
- **Program tab:** swap/rename exercises, change set counts, reorder, add or remove.
- **Data:** stored in your browser's `localStorage` (no server, no account). Use *Setup -> Backup* to copy your data elsewhere. "Clear all data & restart" wipes it.

## Run locally
Open `index.html` in a browser. No build step.

## Host on GitHub Pages
1. Create a new GitHub repository and upload `index.html`, `README.md` and `.nojekyll`.
2. Repo **Settings -> Pages -> Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`, Save.
3. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes on saved data
`localStorage` is saved per browser, per device and per site address. Clearing site data/cookies, using private browsing, or switching browsers/devices means starting fresh unless you restore from a backup. Always open the tracker from the same URL.
