# GeoMapLink

An interactive, single-page world map that highlights countries on hover/click and shows a rich info card (flag, capital, population, and a Wikipedia link). Built with a clean, minimal UI and smooth transitions.

## Live Demo

Open the hosted demo here:

https://taynazdev.github.io/GeoMapLink/

## Features

- Country outlines only by default; fill on hover/click
- Info card with flag, capital, population, and Wikipedia link
- Responsive layout with mobile-friendly tap interactions
- Zoom in/out and reset controls for accessibility of small countries
- Smooth transitions and modern UI
- Data from REST Countries API; rendering via D3 + TopoJSON

## Quick Start

You only need a browser and an internet connection (CDNs are used).

1. Clone or download this repo
2. Open `index.html` in your browser

That’s it. No build step required.

## Project Structure

- `index.html` — Single-file app with embedded CSS and JavaScript
- `README.md` — This documentation

## Tech Stack

- D3.js for SVG rendering and zoom/pan
- TopoJSON world map data (world-atlas)
- REST Countries API for live country info

## Notes

- The info card is positioned to avoid going off-screen when possible
- Zoom controls help access small countries and islands
- Some country names are normalized for better API matching

## Changelog

See `CHANGELOG.md` for a history of notable changes.

## License

See `LICENSE` for details.

