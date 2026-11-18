# Changelog

Every release has its own notes on the
[Releases page](https://github.com/Didtho/jukebox-cab/releases). The full history,
back to version 1.0.2, is on
[jukebox-cab.fr/nouveautes](https://www.jukebox-cab.fr/nouveautes) in four
languages.

## 1.18.1 — 18 November 2026

### Added

- **Your favourites, one star and one button.** A star on every track sets it
  aside, a button in the top bar shows them all, and “Add all” queues the lot.
  Can be switched off in the settings.
- **A guest mode, to share the jukebox for an evening.** The tracks your
  guests play are no longer counted in your listening history, so the Top Mix
  keeps offering your own taste rather than theirs. The last-played date is
  still recorded, so that the next day it does not serve you again what has
  just been heard. The buttons that clear or fill the playlist in one go are
  hidden, the same track cannot be queued twice, and leaving the mode asks for
  the four-digit code. Turn it on in Settings > Running the jukebox.
- **Start over.** A button in the Top Mix settings resets every play count.
  Handy after an evening when other people picked the music: the Top Mix stops
  offering you their taste.
- **An audio cassette joins the screen animations.** Its two reels turn and
  the tape moves from one to the other as the song plays, while the label
  carries the cover art, the artist and the title. Pick it in Settings >
  Screens and video, alongside the turntable, the vinyl cover, the dot banner
  and the wall of covers.
- **Karaoke lyrics now scroll continuously.** The lines used to be replaced as
  a block at every phrase, and the eye lost its place. The whole text of the
  song now glides gently upwards, the line being sung staying slightly above
  the middle of the screen so you can see what is coming. Suggested by a
  jukebox owner.
- **Credits now survive a crash or a power cut.** Until now they lived only in
  memory, so whatever a customer had just paid for was lost. The balance is
  restored at startup, with a message on screen, if the shutdown was abnormal
  and less than three hours old. A normal shutdown restores nothing: the
  machine starts the next day with its usual opening credits.
- **Cover art now appears in the queue.** Instead of a file icon, each line
  carries the album cover, the clip thumbnail or a frame taken from the video.
- **Vinyl crackle, if you want it.** The surface noise of an old LP, played
  over the music, for anyone who would rather hear the record and not just the
  song. Three levels in Settings > Sound, and you hear each one as you pick
  it. Video clips get none.

### Fixed

- **The screensaver came up on top of a video.** A music video or a concert
  filled the screen, and once the idle delay was up the screensaver covered it
  — even though the setting states that it never appears during playback. It
  now checks every way of playing a medium, not just the two it knew about.
- **In credit mode, anyone could shut the jukebox down.** The shutdown and
  quit buttons sit in the top row, within everyone's reach, and one press plus
  a confirmation was enough — even with paid-for tracks still queued. They now
  ask for the four-digit code, just like access to the settings.
- **Search now ignores accents.** Typing “celine” or “beyonce” finally finds
  Céline Dion and Beyoncé. Until now those entries returned nothing at all,
  even though reaching accented letters on a touchscreen keyboard is exactly
  what you want to avoid. The alphabetical filter already ignored them.
- **The countdown switched itself off when you pressed “Test animation”.** The
  date stayed, but nothing happened on the night. You can now try it as many
  times as you like without losing your setting.
- **Changing the metadata source started no scan at all, despite the
  confirmation message.** The library kept showing what it had read in the
  previous mode. The full scan now starts immediately.
- **The settings menu was out of reach on a small screen.** On a
  1024-pixel-wide cabinet only four of the thirteen families were showing,
  with no way to get to the others without a mouse wheel or a touchscreen. Two
  arrows now frame the menu.
- **The settings menu was unreadable on the two light themes.** Its text is
  written in white, which made it all but invisible on Sakura and hard to read
  on Light Wood. Both now have their own colour.
- **In credit mode the counter disappeared exactly where credits are spent.**
  It only showed on the home page, and no longer at all once you entered an
  artist, which is where titles are added. It is now present in every view.
  The playlist's “Clear” button is also hidden now, as the per-line delete
  crosses already were.
- In languages other than French, the countdown test button and its “Enabled /
  Disabled” status stayed in French.
- In the form for adding a web radio, the label of the Genre field read “No
  radio available”, in all four languages.
- **The ring around the mouse pointer stayed on.** The application asks
  Windows to turn that locator off, but the command never went through — one
  character too many stopped Windows from reading it.

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
