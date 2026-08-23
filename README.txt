Morning Routine — Fixed PWA v10

Preserves the currently working Home / Routine / Tracker / timer functionality.

Fixes:
- Home Sound/Voice/Screen Awake buttons now operate the original controls directly.
- Adds an in-app Install App button when Chrome exposes the PWA install prompt.
- Manifest has explicit id, start_url, scope, standalone display, 192/512 PNG icons.
- Service worker has navigation fallback and fresh cache version.

Deploy all files to the root of GitHub Pages.
After deployment, remove the old Morning Routine shortcut/app and open the HTTPS
site in normal Chrome. Tap the page once and leave it open for ~30 seconds;
Chrome's install prompt is subject to browser engagement criteria. The Install App
button will appear when Chrome exposes beforeinstallprompt.
