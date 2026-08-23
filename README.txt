Morning Routine — Stable PWA v5

This build starts from the original known-good timer HTML. No login is included.
The timer engine is not overridden.

Features added separately:
- Progress tracker
- Daily/weekly/monthly compliance
- Streak
- Backup/restore JSON
- PWA manifest
- Offline service worker

Deploy all five files to the root of GitHub Pages:
index.html
manifest.json
sw.js
icon-192.svg
icon-512.svg

Important: after replacing files, test the normal GitHub Pages URL in a new
browser tab before opening any installed PWA. The service worker uses a new
versioned cache (stable-5).
