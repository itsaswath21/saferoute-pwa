SAFEROUTE PWA — ANDROID SETUP

Files:
- index.html: SafeRoute app
- manifest.json: installable app metadata
- service-worker.js: offline caching
- icons/: app icons

IMPORTANT: Android PWA installation and service workers require HTTPS (or localhost). Opening index.html directly from Downloads will let you test the app, but will NOT enable full PWA installation/offline behavior.

EASY FREE HOSTING WITH GITHUB PAGES
1. Sign in to GitHub and create a new public repository named saferoute-pwa.
2. Upload all files and folders from this package (index.html, manifest.json, service-worker.js, icons/).
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the HTTPS URL it gives you on your Android phone in Chrome.
6. In Chrome, tap the three-dot menu > Install app (or Add to Home screen). If shown inside SafeRoute, you can also tap Install SafeRoute.
7. Launch SafeRoute from the home screen. After the first successful load, core app files can be cached for offline use.

You can also deploy the folder to any static web host that provides HTTPS.

SAFETY: This is a fictional-map educational demo with simulated hazards. Do not use it to direct a real evacuation.
