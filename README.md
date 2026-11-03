# josephjackman.com

Joe Jackman's résumé site, served by GitHub Pages from the `main` branch of this repo (the account's user site,
which has the josephjackman.com custom domain).

- `index.html`: the résumé, one self-contained page (only the fonts come from Google Fonts). **Résumé PDF** prints a
  clean résumé from the same content; the print styles are at the end of the `<style>` block. Contact shows the
  city and email only, never a street address or phone number.
- `404.html`: not-found page. It also forwards old game links such as `/horserace/check.html` to
  `/games/horserace/check.html`.
- `altwhiskerwars/`, `infinitehive/`, `horserace/`, `thedeck/`, `lieage/`, `roleplay20/`, `whisker-wars/`: redirects
  from old game addresses to `/games/<name>/`. They keep `?room=` codes and anything after `#`.

## The games

The games live at josephjackman.com/games/, published by the
[games](https://github.com/roamingjackmans-pixel/games) repo (Dungeon Joe's repo). Its `deploy/index.html` is the
games page, and `deploy/library.json` lists where every other game comes from. The Infinite Hive's build is kept
there at `deploy/infinitehive/index.html`. Nothing on this site links to /games/, on purpose: the games are only for
people who have the address.

The game repos ([altwhiskerwars](https://github.com/roamingjackmans-pixel/altwhiskerwars),
[horserace](https://github.com/roamingjackmans-pixel/horserace),
[thedeck](https://github.com/roamingjackmans-pixel/thedeck),
[lieage](https://github.com/roamingjackmans-pixel/lieage) and
[roleplay20](https://github.com/roamingjackmans-pixel/roleplay20)) no longer publish their own GitHub Pages sites.
If one did, it would take over its old address here and that redirect would stop working.

The original Whisker Wars ([whiskerwars](https://github.com/roamingjackmans-pixel/whiskerwars)) still publishes
only a page at `/whiskerwars/` that sends visitors on to Alt Whisker Wars.
