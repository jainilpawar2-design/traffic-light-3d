# 3D Traffic Light Simulator

This is a minimal, interactive 3D traffic light simulation built with **HTML, CSS, and Three.js only** — no frameworks, no build tools, no extra libraries. Single file, runs directly in the browser.

## Live Demo

open `https://trafficlightsimulator3d.netlify.app` in any  browser

## What It Does

Simulates a real-world traffic signal at an intersection:

- Cycles automatically through **GREEN → YELLOW → RED** with realistic timing
- Live countdown showing seconds until the next state change
- Pause/resume the auto-cycle with one click
- Fully explorable 3D scene — drag to orbit the camera, scroll to zoom

## Tech Stack

- **HTML** — page structure
- **CSS** — all styling (dark control-panel UI, layout, typography)
- **Three.js** — the only JavaScript library used, for the entire 3D scene

No Orbit Controls addon, no UI frameworks, no external CSS libraries. Camera orbit/zoom controls are hand-written using vanilla pointer and wheel events.

## Geometry Used

Only 3 primitive shapes make up the whole scene:

| Shape | Three.js Geometry | Used For |
|---|---|---|
| Plane | `Plane Geometry` | Road surface |
| Box | `Box Geometry` | Pole + signal housing |
| Sphere | `Sphere Geometry` | Red, yellow, and green lamps |

## Controls

| Action | Input |
|---|---|
| Orbit camera | Click + drag |
| Zoom | Scroll wheel |
| Pause/resume signal cycle | Click the button in the HUD |

## Why This Project

A practical, real-world use case — traffic signal behavior — visualized in 3D. Useful as a teaching aid, a driving-school demo, or a quick reference for how signal timing sequences work.

## Run Locally

```bash
git clone https://github.com/jainilpawar2-design/traffic-light-3d.git
cd traffic-light-3d
open traffic-light-3d.html   # or just double-click the file
```

## License

MIT — free to use, modify, and share.
