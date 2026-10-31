# josephjackman.com

Home page for josephjackman.com, served by GitHub Pages from the `main` branch.

- `index.html`: landing page with a card for each game (Alt Whisker Wars, The Infinite Hive, Horse Race, The Deck)
- `whisker-wars/`: redirect from an old address to `/altwhiskerwars/`
- `infinitehive/`: The Infinite Hive, an incremental game in one self-contained page (served at `/infinitehive/`).
  It is built by the game's own `node build.mjs`; to update it, copy the new build over `infinitehive/index.html`.
- `404.html`: not-found page

Alt Whisker Wars, Horse Race and The Deck live in their own repos,
[altwhiskerwars](https://github.com/roamingjackmans-pixel/altwhiskerwars),
[horserace](https://github.com/roamingjackmans-pixel/horserace) and
[thedeck](https://github.com/roamingjackmans-pixel/thedeck), and show up at `/altwhiskerwars/`, `/horserace/` and
`/thedeck/` because this site has the custom domain.

The original Whisker Wars ([whiskerwars](https://github.com/roamingjackmans-pixel/whiskerwars)) is no longer on the
site: its repo now publishes only a page at `/whiskerwars/` that sends visitors to `/altwhiskerwars/`.
