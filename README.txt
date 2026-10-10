SAFEROUTE — VIT VELLORE CAMPUS PILOT

Deploy:
1. Upload every file and the icons folder to the ROOT of the existing GitHub repository.
2. Commit changes to main. GitHub Pages should redeploy automatically.
3. On iPhone, open https://itsaswath21.github.io/saferoute-pwa/ in Safari. If it appears unchanged, close the app and reload the page; if needed remove and re-add the Home Screen app after the update deploys.

Features:
- Interactive OpenStreetMap centered on the VIT Vellore area.
- Place search via Nominatim and road-route estimates via OSRM public demo services (internet required; public services have usage limits and are not guaranteed).
- Device location button (requires user permission).
- Floor plan image preview and local-device details storage.
- Indoor routing is intentionally NOT enabled: verified floor plans, corridors, stairs, accessible routes, exits, and approval from campus facilities/security are required first.

IMPORTANT SAFETY / DATA NOTES:
- This is a student prototype, not an official VIT app and not a certified emergency system.
- Map pins and outdoor paths are based on public map services and may be incomplete, inaccurate, closed, or not pedestrian-accessible. Verify before relying on them.
- Hazard switches are simulations only; there is no live sensor feed or campus alert integration.
- In a real emergency, follow official campus alarms, security staff, and posted evacuation signs.
- Uploaded floor-plan images remain on the current device in this prototype; they are not sent to a server.
