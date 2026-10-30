# josephjackman.com

Home page for josephjackman.com, served by GitHub Pages from the `main` branch.

- `index.html`: landing page with a card for each game (Whisker Wars, Alt Whisker Wars, The Infinite Hive, Horse Race, The Deck)
- `whisker-wars/`: redirect from the game's old address to `/whiskerwars/`
- `infinitehive/`: The Infinite Hive, an incremental game in one self-contained page (served at `/infinitehive/`).
  It is built by the game's own `node build.mjs`; to update it, copy the new build over `infinitehive/index.html`.
- `404.html`: not-found page

Whisker Wars, Alt Whisker Wars, Horse Race and The Deck live in their own repos,
[whiskerwars](https://github.com/roamingjackmans-pixel/whiskerwars), [altwhiskerwars](https://github.com/roamingjackmans-pixel/altwhiskerwars),
[horserace](https://github.com/roamingjackmans-pixel/horserace) and
[thedeck](https://github.com/roamingjackmans-pixel/thedeck), and show up at `/whiskerwars/`, `/horserace/` and
`/thedeck/` (and `/altwhiskerwars/`) because this site has the custom domain.
