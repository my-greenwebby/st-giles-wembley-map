# St. Giles Wembley Explorer — PWA

This package converts the supplied St. Giles Wembley Penang interactive map into an installable Progressive Web App.

## Included
- Original interactive map and destination data
- Search and category filters
- Walking / driving route display
- Evening food circuit
- Google Maps hand-off
- Web App Manifest
- Service Worker
- Android home-screen installation support
- PWA icons generated from the supplied image

## Run
A PWA must be served from HTTPS or localhost; opening `index.html` directly with `file://` will not enable the service worker.

Example:
- VS Code + Live Server
- `python -m http.server 8080`

Then open:
`http://localhost:8080/`

For an Android phone, host the folder on an HTTPS website and open it in Chrome. Chrome should offer **Install app / Add to Home screen**.

## Offline note
The application shell and successfully cached external resources can work offline. Live map tiles still depend on the map provider/network and are not bundled as an offline map database.
