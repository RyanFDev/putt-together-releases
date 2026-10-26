# Patch notes

[Latest download](https://github.com/RyanFDev/putt-together-releases/releases/latest)
 · [Getting started](GETTING_STARTED.md)

## 0.1.8 — 26 October 2026

- Add the nine-hole Putt 'R Cade course, editable Message Signs and arcade wall graphics.
- Expose supported resize axes directly through Q/E, wheel and numeric Tab options.
- Add optional hole boundaries, free practice placement independent of hole bounds,
  explicit portal pairs and branching bot guides with optional Stop in region behavior.
- Add shot-power wheel and keyboard controls with brief feedback, improve input
  consistency and protect unfinished strokes from delayed mouse input.
- Add four numbered tee slots, improve close-ball putter contact and match boost
  activation to the visible pad.
- Add optional experimental bot AI, off by default in round setup, with improved
  routing, human putting priority and next-hole recovery.
- Add optional F2 overlays for boundaries, prop zones and bot planning targets.
- Known issue: experimental bots can still stutter and struggle on complex holes,
  especially with several bots playing.

[Full notes](notes/0.1.8.md) · [Release and download](https://github.com/RyanFDev/putt-together-releases/releases/tag/v0.1.8)

## 0.1.7 — 23 October 2026

- Group personal and premade parks, add favorites, and improve library filtering
  and sorting. Open parks faster with a loading screen and fix a false
  unsaved-changes warning during loading.
- Organize Settings into Display, Putting, Comfort and Park tabs, with explicit
  window resolutions and host controls for time of day, daylight pause and day length.
- Add Frictionless Marble runs, gentle and steep downhill funnels, and improved
  Chain Lift exits and backward-return contacts.
- Show clearer piece dimensions, resize indicators and size/drop badges, with
  related variants grouped in the library.
- Restore **N** to advance after holing out, and **Tab** cursor access to the
  **Next hole / Finish round** button with Putter equipped.
- Show formatted patch notes and expandable release history in the game.

[Full notes](notes/0.1.7.md) · [Release and download](https://github.com/RyanFDev/putt-together-releases/releases/tag/v0.1.7)

## 0.1.6 — 23 October 2026

- Repair missing path entrances and awkward joins in the included outdoor parks,
  including paths that ran beneath curbs or into greens in 0.1.5.
- Improve the path tool's ramps along slopes and across adjoining curb pieces.
- Improve Willowbend's walking bridge and drawbridge approaches.
- Smooth the lighting across fitted path entrances.

After updating, reopen the bundled courses from **Explore parks** for the
corrected layouts. Existing personal saved copies remain unchanged.

[Release and download](https://github.com/RyanFDev/putt-together-releases/releases/tag/v0.1.6)

## 0.1.5 — 23 October 2026

- Refreshed all eleven included course layouts, paths, rest areas, grounding and
  green boundaries; softened surrounding terrain and repaired furniture details.
- Planted the spaces between holes and added six reusable landscaping props:
  river and split boulders, a flat stone, mossy rocks, ferns and a flowering shrub.
- Added Willowbend's creek, bridges, and Willow Island moat hole with a timed,
  resizable drawbridge operated from either bank.
- Added saved ball and putter customization, visible to friends in multiplayer.
  The starter collection is unlocked; progression rewards are not implemented.
- Added quick connection/grid switches, an independent visible placement grid,
  and curb-shaped ramp entrances for paths.
- Added responsive window/aspect handling, fullscreen preferences and Alt+Enter.
- Fixed the false unsaved-changes prompt after a quick second course-open click.

[Release and download](https://github.com/RyanFDev/putt-together-releases/releases/tag/v0.1.5)

## 0.1.4 — 23 October 2026

A maintenance release of the Windows beta. The courses, controls and gameplay
are unchanged from 0.1.3. You can install it through **Check for Updates** or
download the complete ZIP.

[Release and download](https://github.com/RyanFDev/putt-together-releases/releases/tag/v0.1.4)

## 0.1.3 — 23 October 2026

The first public Windows beta, with an in-game updater for future releases.

- Play included garden and neon arcade courses, or build your own with tracks,
  modular buildings, terrain tools and moving obstacles.
- Putt solo or host a park for up to four participants, with optional bots in
  spare places. Players can build together and strike their own balls at the
  same time.
- Choose Easy or Advanced putting, adjust the mouse stroke and use the aiming
  view to read a line.
- Save parks and blueprints, and recover recent unsaved course edits from the
  park browser.
- Check for updates from the menu, read the release notes, download a new build
  and restart when ready. Updates retain the previous installation and keep
  saved parks and settings separate.

If you're coming from an older development build, download and extract this
release or a newer one once to get the updater.

[Release and download](https://github.com/RyanFDev/putt-together-releases/releases/tag/v0.1.3)

## About this beta

Windows builds are unsigned. Multiplayer is player-hosted; internet connections
need a route to the host, and there's no matchmaking, platform invitation system
or host migration yet. See [multiplayer](MULTIPLAYER.md) and
[troubleshooting](TROUBLESHOOTING.md) for setup and help.
