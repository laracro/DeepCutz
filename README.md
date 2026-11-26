# DeepCutz

A daily music trivia game where rare answers win.

- 7 questions a day (tracks A1–B3), one answer each, 30 seconds per track.
- Any correct answer scores; the fewer players likely to name it, the more points (up to 100 per track, 700 total).
- Tiers: 📻 Hit · 💿 B-Side · 🔥 Deep Cut · 💎 Holy Grail · 🔇 Miss.
- Questions span genres, decades and countries: albums, song titles, chart #1s, Grammys, classical, jazz, hip-hop, metal, reggaeton and more.
- "Free dig" mode plays a random set any time. Copy result shares your score as an emoji row.

## Run it

It's a single static file. Open `index.html` in a browser, or host it on any static host (e.g. GitHub Pages).

## Notes

Rarity percentages are hand-estimated, not from real player data. Questions live in the `CRATE` array in `index.html`; each answer line is `weight Title|alias|alias ~ Artist`.
