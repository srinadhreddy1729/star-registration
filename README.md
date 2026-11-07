# Asteria Star Registry

A dependency-free HTML/CSS/JavaScript website with an animated, perspective-projected galaxy.

## Run
Open dist/index.html in a browser, or serve dist using any static web server.

## Features
- 8,000 animated galaxy particles, drag to orbit, scroll/controls to zoom
- Register symbolic stars with a name, recipient, date, message, and color
- Fly to a star from its ID or search by exact name/ID
- Local browser persistence and downloadable text dedication

## Storage
Records are saved in localStorage on the current browser and origin. This is not a shared multi-user database. Clearing browser storage removes registrations. Star positions and sectors are artistic, not astronomical coordinates.

## Files
index.html: markup; style.css: responsive design; app.js: galaxy renderer and registration logic.
