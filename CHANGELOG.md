# Changelog

Every release has its own notes on the
[Releases page](https://github.com/Didtho/jukebox-cab/releases). The full history,
back to version 1.0.2, is on
[jukebox-cab.fr/nouveautes](https://www.jukebox-cab.fr/nouveautes) in four
languages.

## 1.18.0 — 11 November 2026

### Added

- **Choose what fills the screen while a song plays.** On a cabinet with a
  single screen the library simply stayed there. Four animations are now
  offered, and you pick one: **45 rpm turntable** (the disc change played in
  full, then the platter spins with the cover as its label), **cover on
  vinyl**, **dot-matrix board** (artist and title scrolling in large dotted
  letters) and **wall of covers**. Each has a Hide button, and none of them
  takes over the screen on the first song of a run — that is when you are
  still filling the queue.
- **The queue as a wall of covers.** The playing track takes four tiles and
  carries its name, the rest follow in playing order. Touch a cover to play
  it; tracks sharing the same artwork are grouped under one tile that unfolds
  into its titles.
- **The grid shows covers edge to edge.** A sixth tile shape, and the new
  default: the artwork fills its tile and the name sits over it.
- **A What's new screen** after an update, shown once, listing what changed.
- **Settings completely rethought.** Thirteen families listed down the left
  instead of collapsed sections, a search box at the top, and every setting
  explained under its own label. Previously you arrived on a page where nothing
  was visible and had to remember which section a setting lived in.
- **Step-by-step help inside the application.** A **?** button opens a guide for
  the library, the grid, web radios, karaoke, CD import and the countdown — the
  same guides as the website, which a cabinet with no browser and no keyboard
  could not reach.
- **Search by album.** A third button next to Artist and Title.
- **The alphabet bar can filter the artist grid** instead of listing tracks.
  Optional; the previous behaviour stays the default.
- **A vertical slider for the volume**, alongside the rotary knob. On a
  touchscreen you touch the height you want directly.
- **New Sakura theme**, which had been sitting on disk without ever being
  offered.

### Fixed

- **CD import: the cover is now looked up elsewhere** when the main artwork
  database has none. The album was recognised, but the tile stayed empty.
- **CD ripping: the track number stored in each file now follows its name.** A
  disc ripped in several passes came out interleaved in playback order.
- **The playlist showed a grey rectangle** in the middle of its styling, in ten
  themes out of eleven.
- **Top Mix:** messages were not translated, and the header button stayed
  misshapen after the first mix.
- **The track list reserved an empty band at the bottom** that nothing ever
  filled.
