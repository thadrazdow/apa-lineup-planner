# APA Lineup Planner

Plan legal APA 8-ball and 9-ball lineups under the 23-point skill level cap.

**Live:** https://thadrazdow.github.io/apa-lineup-planner/

- **Set up once:** enter your 5–8 players, their names and skill levels, and the format. It's saved in your browser on that device.
- **Plan:** mark each player **In** (definitely playing), **Maybe** or **Out**. Every legal 5-player lineup is listed, highest total first. If two players have the same skill level and either could fill a spot, both names are shown ("Joe / Priya").
- **Match night:** tap **Put up** as each player goes to the table. It tracks the cap you've used and only lets you put up players who still leave room for a legal lineup.
- **Offline:** after the first visit it works without signal. Add it to your home screen to open it like an app.

Static files only, no build step: `index.html`, `sw.js` (offline cache), `manifest.webmanifest` and icons. The app opens from cache and refreshes in the background, so after a push, phones get the new version the second time they open it. If you add a new file, also add it to `ASSETS` in `sw.js` and bump `CACHE`.
