THRYLOS MATCH HUB — 7 November 2026

HOW TO PUBLISH (GITHUB PAGES)
1. Create a NEW public repository called olympiacos-match-hub.
2. Upload all five app files: index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png. The optional seed.json/README.txt files need not be uploaded.
3. Go to Settings > Pages > Deploy from a branch > main > / (root) > Save.
4. Open https://YOURUSERNAME.github.io/olympiacos-match-hub/ in Safari.
5. Share > Add to Home Screen > Open as Web App > Add.

FUNCTIONS
- Olympiacos priority dashboard with fixture countdown
- Competition filters: Greek Super League, Premier League, Champions League, Europa League, Conference League, Greek Cup (in Olympiacos/All list)
- Live scores & fixtures via the unofficial ESPN browser-readable scoreboard API
- Graceful fallback to a snapshot of known Olympiacos fixtures dated 7 Nov 2026
- UK/Greece/device timezones, 14/30/60/90 day range, add-to-calendar (.ics)
- Local data cache, offline shell via service worker, manual/periodic refresh

CAVEATS
The ESPN endpoint is unofficial and can break or have missing leagues/fixtures. Live coverage cannot be guaranteed. The bundled snapshot is not a real-time feed. Fixture kickoffs and TV schedules can change. Calendar reminders are only set once you import .ics into your calendar; the web app does not send push notifications.
