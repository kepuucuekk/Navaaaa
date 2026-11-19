ARYA TRADING JOURNAL V7.3 — SELF-CONTAINED VISUAL ASSETS

All dashboard artwork is embedded directly inside index.html as data URIs.
There is NO assets folder requirement. Card backgrounds, bottom navigation artwork,
header artwork, and logo are embedded in the HTML.

Deploy every file inside this folder to the GitHub Pages publishing root/branch.
Required root files: index.html, sw.js, manifest.webmanifest, icon.png, icon.svg.
Do not upload only index.html if you want the PWA install icon and offline cache.

After deployment on iPhone:
1. Open the GitHub Pages site once in Safari.
2. Refresh the page.
3. If an older PWA remains cached, close the installed app fully and reopen Safari/site;
   allow the V7.3 service worker to install, then reopen the home-screen app.

All visual assets are embedded, so a missing assets/ directory cannot break the cards.


V7.4 COMPACT ICON UPDATE
- Reduced the four dashboard statistic-card icons to match the reference scale.
- Reduced all five bottom-navigation icons while preserving active-state glow and navigation behavior.
- No trade logic, storage, calendar, analytics, or tools behavior changed.
- Service worker cache updated to v7.4.
