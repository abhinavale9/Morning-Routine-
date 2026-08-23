Morning Routine PWA v3

Replace the existing GitHub Pages files with these five files:
- index.html
- sw.js
- manifest.json
- icon-192.svg
- icon-512.svg

This version uses a versioned service-worker cache (v3), updateViaCache:none,
and network-first fetching for index.html so new deployments are picked up.

After committing, wait for GitHub Pages to deploy. If an installed PWA still
shows the old version, remove the old installed app/site data once and
reinstall it.
