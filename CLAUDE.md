# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static single-page HTML travel itinerary for a Da Nang + Hoi An trip (14–18 May 2026, 9 pax). The entire app lives in `DaNang_HoiAn_Itinerary_w_map.html`.

## Structure

- **Single HTML file** with inline CSS and JavaScript — no build tools, bundler, or package manager
- Tabbed UI (Itinerary, By age group, Budget, Night markets, Tips & packing) controlled by vanilla JS
- Collapsible day cards for the 5-day itinerary
- Embedded Leaflet.js map loaded from CDN
- A `.venv/` Python virtual environment exists but is not used by the HTML app

## Development

Open the HTML file directly in a browser — no server required. To preview changes, just refresh.
