# Security Cam Grid

A retro CCTV / surveillance terminal interface displaying a dynamic 4-camera grid of live public webcam feeds from around the world.

## Features

- **Live Streams**: Supports HLS (`.m3u8`) and YouTube live camera streams.
- **Categorized Feeds**: Filter by region (North America, Europe, Asia, Africa, South America, Oceania) and category (Traffic, Beach, Resort, City, Nature).
- **Retro CRT Aesthetic**: CRT scanline effects, phosphor-green HUD, and tracking animations.
- **Dynamic Shuffling**: Randomize individual slots or shuffle all active camera feeds.
- **Controls & Shortcuts**: Quick hotkeys (e.g. `Space` or `R` to shuffle) and full-screen view.

## Live Demo

View the live dashboard at: [https://namoran.github.io/security-cam-grid/](https://namoran.github.io/security-cam-grid/)

## Usage

Simply open `index.html` in any modern web browser or serve it via a local static file server:

```bash
python3 -m http.server 8000
```
