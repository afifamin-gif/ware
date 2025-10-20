# Restaurant Finder — OSM + Overpass (No Paid APIs)

## What this is
A single-file web app that lets you draw on a map and list restaurants from **OpenStreetMap** inside your shape. No Yelp/Google. No server. Host anywhere.

## Use
1) Open `index.html` locally, or host it (Netlify Drop / GitHub Pages).
2) Click the square/shape tool, draw an area, then **Search in Shape**.
3) Optional filters: name contains, cuisine (OSM tag).

## Notes
- Data source is OpenStreetMap via Overpass API. Please zoom in and search reasonable areas (don’t hammer Overpass).
- The app has a small in-tab cache so the same query won’t re-hit the API immediately.
- You can switch Overpass endpoints in the `OVERPASS_ENDPOINTS` array if one is slow.

## Hosting
- **Netlify Drop**: drag-and-drop `index.html` (no config needed).
- **GitHub Pages**: create a repo and put `index.html` at root.
- **Any static host** works.

Enjoy!
