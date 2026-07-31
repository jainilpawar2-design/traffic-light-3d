# Signal Sim - 3D Traffic Light Simulator

A 3D traffic light simulation made with HTML, CSS, and Three.js. It cycles through green, yellow, and red like a real traffic signal, with a live countdown timer.

## What it does

- Auto-cycles through GO (green), CAUTION (yellow), and STOP (red)
- Shows a countdown until the next light change
- Pause/resume button to freeze the cycle
- Drag to rotate the camera around the scene
- Scroll to zoom in and out

## Tech used

- HTML
- CSS
- Three.js (only library used, no extra addons)

Camera controls (drag to orbit, scroll to zoom) are written from scratch, not using any external controls library.

## Shapes used

- Plane - road
- Box - pole and housing
- Sphere - the 3 lights (red, yellow, green)

## How to run

Just open the html file in a browser. No install or server needed.

## Controls

- Click and drag: rotate camera
- Scroll: zoom in/out
- Button in the panel: pause/resume the light cycle
