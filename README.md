# anystarregistration

A dependency-free HTML/CSS/JavaScript website with an animated, perspective-projected galaxy.

## Run
Open dist/index.html in a browser, or serve dist using any static web server.

## Features
- 8,000 animated galaxy particles, drag to orbit, scroll/controls to zoom
- Register symbolic stars with a name, recipient, date, message, and color
- Fly to a star from its ID or search by exact name/ID
- Local browser persistence and downloadable high-resolution PNG certificate with name, ID, dedication date, full message, recipient, sector, virtual coordinates, glow, and registration date (for new registrations)

## Storage
Records are saved in localStorage on the current browser and origin. This is not a shared multi-user database. Clearing browser storage removes registrations. Star positions and sectors are artistic, not astronomical coordinates.

## Files
index.html: markup; style.css: responsive design; app.js: galaxy renderer and registration logic.

Messages support up to 3,000 characters. Certificate height expands to preserve the full dedication. Existing browser registrations remain available.

## Mobile layout
Phones use a scrollable layout, 44px or larger primary touch targets, a dedicated galaxy gesture area with pinch zoom, and a scrollable registration dialog. Checked at 320px and 390px viewport widths.

## Pages
Home: index.html; Explore: explore.html; Register: register.html; My Stars: my-stars.html. Keep all HTML, CSS and JS files together. Serve with a static server (for example python3 -m http.server 8000) or deploy to GitHub Pages. No build step required. universe.js renders an artistic eight-planet solar system.
