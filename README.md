# Website previews

The web-hobbing/ folder contains the ready-to-publish website build.

Enable Settings → Pages → Deploy from a branch → main → / (root).

Website address after deployment: https://yuze-rgb.github.io/preview/web-hobbing/

Only public website assets are included. The original PDF catalogue, ZIP archives and source repository history are excluded.

To update: build the source project with npm run build -- --base=/preview/web-hobbing/, run node scripts/check-public-assets.mjs, and copy only dist contents into web-hobbing/. Never copy private files or .git history.
