# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Fixed
- Weather card: "°C" is no longer cut off at the right edge (big numbers 28 px instead of 32 px, and the station name gives way first; card-mod).
- Block bars: the empty blocks are now clearly visible (opaque track in the field line colour), so you can read the full range.
- Light mode: the weather sun is darker (3:1 against the card) and stays visible.
- Card titles are 20 px and no longer larger than section titles; the thermostat title is in capitals like the other card titles (card-mod).
- Card colour is set as a hex value, so the frontend can derive `rgb-card-background-color`.
- Sidebar cursor is 12 px instead of 10 px (card-mod).

### Changed
- Tile features are 42 px high again (Home Assistant default) instead of 32 px, for easier tapping on phones.
- Tile icons keep their coloured plate, so the icon is recognisable as its own button on touch screens.
- The more-info dialog uses the theme font (card-mod).
- Titles try a separate optional font slot first (`Bitmap Home Pixel Titles`); the README now suggests a pixel font for titles only and explains why.

### Docs
- README: font slots, known limits for the dialog font, keyboard focus without card-mod and half-filled blocks.

## [1.1.0] - 2026-11-25

### Changed
- Type sizes follow a character set: small 12 px, normal 16 px, titles 20 px, double 24 px, 32/40/48 px for big numbers; line heights 1.5 and 1.25, so text sits on a 4 px grid. 10 px text is gone.
- 12 px gaps between cards in sections, so the window frames do not touch.
- State colours from the theme palette: open covers light green, playing media purple, heating orange, heat/cool yellow; cloudy and partly cloudy weather in the palette grey.
- Weather icons in the palette: yellow sun, cream clouds over blue-grey, blue rain (dark and light).

### Changed (card-mod)
- Tile icons stand free like in a menu, without the coloured plate; the plate comes back on hover.
- Tile features are 32 px high instead of 42 px, block bars get flatter blocks; 8 px between feature buttons.

### Docs
- README images show 1.1.0.

## [1.0.0] - 2026-11-24

### Added
- First release: one theme with dark and light mode.
- Cards, badges and dialogs as dialogue windows with a double pixel frame, square corners everywhere.
- Night sky with pixel stars behind dashboards (dark), pale sky with pixel clouds (light).
- One monospace font stack for all text, with an optional slot for a pixel font you add yourself.
- Optional card-mod rules: ▶ cursor in front of switched-on tiles and the selected sidebar entry, block bars on tile sliders (per tile with the class `bitmap-blocks`), notched pixel corners, upper-case headings, a clearer keyboard focus on tiles.
