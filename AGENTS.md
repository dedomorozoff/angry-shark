# AGENTS.md

## Project

Single-file browser game "Голодная Акула" (Hungry Shark) — `index.html` with embedded CSS and JS. No build step, no dependencies.

## Run

Open `index.html` in a browser. No server required.

## Structure

- `index.html` — entire game: HTML, CSS, and JavaScript in one file
- No build system, no tests, no linting configured

## Notes

- Touch controls (virtual joystick) activate automatically on mobile devices
- Camera follows the shark on touch; mouse-driven edge-scrolling on desktop
- Game state (best score) stored in `localStorage`
- All game logic, rendering, and UI are in the single file — edit carefully
