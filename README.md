# Website preview

Static website build for https://yuze-rgb.github.io/preview/.

Enable GitHub Pages in Settings → Pages: Source = Deploy from a branch, Branch = main, Folder = / (root), then Save.

This repository contains only the public website build and selected product images. The original product catalogue PDF, archives and source repository history are not included.

To refresh, build the source project with `npm run build -- --base=/preview/`, run its `node scripts/check-public-assets.mjs` check, and copy only the resulting dist contents here. Do not copy the source repository .git directory or private files.
