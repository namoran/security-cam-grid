# Security Cam Grid

A retro CCTV / surveillance terminal interface displaying a dynamic 4-camera grid of live public webcam feeds from around the world.

## Features

- **6,100+ Live Streams**: High-reliability public traffic cameras, city surveillance, coastal/beach feeds, mountain passes, and wildlife preserves with 100% open CORS and HTTPS support.
- **Interactive Tactical Radar Map**: Browse all 6,100+ cameras across the globe on an interactive dark surveillance map (`M` key or `MAP VIEW` button) with smooth clustering, keyword search, and one-click camera tuning for slots 1–4.
- **Categorized Feeds & Filters**: Filter by camera type (Traffic, Urban, Beach, Mountain, Nature), continent, country, and state.
- **Retro CRT Aesthetic**: CRT scanline effects, phosphor-green HUD, tracking animations, and tactile controls.
- **Dynamic Shuffling**: Randomize individual camera slots or shuffle all active feeds with `Space` or `R`.
- **Audio & Fullscreen Support**: Select any camera tile to unmute its audio stream or toggle full-screen view.

## Live Demo

View the live dashboard at: [https://namoran.github.io/security-cam-grid/](https://namoran.github.io/security-cam-grid/)

## Usage

Simply open `index.html` in any modern web browser or serve it via a local static file server:

```bash
python3 -m http.server 8000
```

### Hotkeys

- `Space` / `R`: Shuffle all 4 cameras
- `M`: Toggle Tactical Radar Map View
- `Esc`: Close Map View
