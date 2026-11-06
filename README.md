# Haven House · College Hostel Management

A responsive, static front end for a college hostel. Open `index.html` in a modern browser to get started. No install or build step is required.

## Pages

- `index.html` — overview metrics and quick links
- `students.html` — searchable student directory
- `update-student.html` — visible student picker and add/edit form
- `rooms.html` — searchable rooms with capacity and occupancy
- `allocations.html` — create allocations, review stays, and vacate rooms

Each page has a matching local SVG illustration under `assets/`. Shared presentation and behavior are in `assets/styles.css` and `assets/app.js`.

## Demo data and storage

The app starts with sample students, rooms, and allocations. Changes are saved in the browser's `localStorage`, so they remain on that browser and device. Use the pages over a local static web server if your browser restricts storage for files opened directly; for example, from this folder run `python -m http.server 8000` and visit `http://localhost:8000`.

This is a front-end prototype and does not connect to a database or provide user authentication. The records mirror the requested students, rooms, and allocations fields; connect a server/API to make the data shared across wardens and devices.
