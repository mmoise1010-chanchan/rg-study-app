RG Study App — iPad PWA package

FILES
- index.html: the complete RG Study App
- manifest.webmanifest: installable-app metadata
- sw.js: offline cache/service worker
- icon-192.png and icon-512.png: Home Screen icons

IMPORTANT
A PWA must be served from HTTPS (or localhost during development). Opening these files directly from the iPad Files app will not activate the service worker.

INSTALL ON IPAD
1. Upload this entire folder to an HTTPS static host.
2. Open the resulting website in Safari on the iPad.
3. Tap Share.
4. Tap Add to Home Screen.
5. Open RG Study from the new Home Screen icon.
6. After the first successful online load, the service worker caches the app for offline use.

Keep all five files together when hosting.
