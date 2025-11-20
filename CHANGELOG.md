# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project aims to follow
Semantic Versioning once releases begin.

## [Unreleased]

- Planned: Versioning and release notes structure

## 0.2.0 - 2025-11-20

### Added
- Geographic reference lines: Equator, Tropics of Cancer and Capricorn, Arctic and Antarctic Circles (grey, on top of countries)
- Timezone meridian lines with UTC offset labels (blue, subtle)
- Infinite horizontal scrolling with seamless wrapping (3 map copies with auto-repositioning)
- Mobile viewport optimizations with dynamic viewport height support

### Changed
- Map styling: countries now have white fill by default, purple on hover/click
- Ocean background: blue fill added
- Interaction: changed from hover to click-only for better card usability
- Layout: compact header, footer, and margins; zoomed out projection to eliminate vertical scrolling
- Timezone lines: made more subtle with reduced opacity and lighter colors

### Fixed
- Pointer events on ocean to allow clicking through to countries
- Map loading issue with latitude lines rendering
- Infinite scroll wrapping using proper projection width calculations
- Mobile viewport: map now fills entire designated area

### Removed
- National anthem audio player feature (completely removed)

## 0.1.0 - 2025-11-15

### Added
- Initial interactive single-page app (`index.html`) with D3.js world map, hover/click interactions, info card, and zoom controls. ([f2acd1d])
- README with live demo link and project overview. ([9991f65])
- CHANGELOG.md file with initial version tracking

<!-- Commit references -->
[f2acd1d]: https://github.com/TaynazDev/GeoMapLink/commit/f2acd1d
[9991f65]: https://github.com/TaynazDev/GeoMapLink/commit/9991f65
