# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

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
