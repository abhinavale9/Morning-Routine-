Morning Routine — Installable PWA v9

This package preserves the currently working Home / Routine / Tracker build.

PWA installation improvements:
- Real 192x192 and 512x512 PNG icons
- Explicit manifest id, start_url, scope, standalone display
- PWA metadata and apple-touch-icon
- Fresh service-worker cache version

Deploy all files in this folder to the ROOT of the GitHub Pages site.

After deployment, test the HTTPS GitHub Pages URL in normal Chrome. Remove any
old Morning Routine shortcut/app first. Then Chrome should offer "Install app"
when the site is recognized as installable.

If Chrome still only offers "Add to Home screen", open Chrome DevTools
Application > Manifest and check the Installability section for the exact
reason Chrome is not offering installation.
