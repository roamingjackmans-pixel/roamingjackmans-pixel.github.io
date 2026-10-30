# josephjackman.com

Home page for josephjackman.com, served by GitHub Pages from the `main` branch.

- `index.html`: landing page with a card for each game (Whisker Wars, The Infinite Hive, Horse Race)
- `whisker-wars/`: redirect from the game's old address to `/whiskerwars/`
- `infinitehive/`: The Infinite Hive, an incremental game in one self-contained page (served at `/infinitehive/`).
  It is built by the game's own `node build.mjs`; to update it, copy the new build over `infinitehive/index.html`.
- `404.html`: not-found page

Whisker Wars and Horse Race live in their own repos, [whiskerwars](https://github.com/roamingjackmans-pixel/whiskerwars)
and [horserace](https://github.com/roamingjackmans-pixel/horserace), and show up at `/whiskerwars/` and `/horserace/`
because this site has the custom domain.
