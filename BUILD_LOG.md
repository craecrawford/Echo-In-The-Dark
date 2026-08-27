# Echo in the Dark — Build Log

## Project
A browser-based 2D maze survival game built with HTML, CSS, and vanilla JavaScript.

## Implemented Features
- Procedurally generated maze with dense, single-route passages
- Maze growth every 30 seconds while preserving player position
- Glowing green arrow player controlled with arrow keys
- Flashlight visibility system with progressive flickering
- Battery drain: 3% per second for the first 10 seconds, then 5% per second
- Blue diamonds restore 25% battery and respawn away from the player
- One gold diamond restores 50% battery
- Survival scoring: 1 point every 3 seconds
- Pause with Escape and restart with R
- Game ends when flashlight battery reaches 0%
- Persistent high score using local browser storage
- Layout scales to fit a 13-inch laptop screen without page scrolling

## Files
- `index.html` — game structure and screens
- `style.css` — visual style and responsive layout
- `game.js` — maze generation, controls, timer, pickups, and rendering

## Deployment
The game is ready for GitHub Pages from the `main` branch and repository root.
