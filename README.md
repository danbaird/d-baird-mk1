# D Baird Mk1 · 2 m EDF glider

Interactive 3D viewer, specs and RealFlight controller setup for the D Baird Mk1: a 2 m fiberglass glider with a 64 mm EDF that rises out of the fuselage on a parallelogram lift.

Live page: GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Updating
- **Download button:** upload the RealFlight export (e.g. `D_Baird_Mk1_V1.1.zip`) to the repo root, then set `DOWNLOAD.url` near the top of the script in `index.html`. A Swap Pages URL works too.
- **Forum button:** paste the thread URL into `FORUM_URL`. It stays hidden until set.
- **Custom domain later:** add a `CNAME` file containing e.g. `mk1.<your-domain>` and point a DNS CNAME record at `danbaird.github.io`.

Static files only: `index.html`, `mk1_mesh.js` (geometry), `three.min.js` (three.js r128, MIT, see THREE_LICENSE.txt).
