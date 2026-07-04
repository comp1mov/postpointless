# post.pointless Vercel Preview

Deploy root for the current post.pointless baseline.

Source snapshot:

`../pointcloud-viewer-v0_98_share_release.html`

Preview entry:

`index.html`

Public release URL:

https://postpointless.vercel.app/

Inspect URL:

https://vercel.com/gregtsv23-6635s-projects/vercel-preview/5EpufTikAmys2mEnGpzCcWGfsp8y

Production deployment:

https://vercel-preview-mp26b6n10-gregtsv23-6635s-projects.vercel.app

## Notes

- This folder is intentionally small and static.
- Do not deploy the whole `PointClouds` workspace.
- Point cloud files are loaded by the browser from the user's local file picker.
- The app imports Three.js and Tweakpane from CDN import maps.
- Default export output is `Screen / Current View`, so image and video capture should keep the current viewport aspect.
- `Rec with UI Button` can turn the white UI dot into a quick record start/stop control.
- `Controls -> Help` and the `?` button next to the title open the help/hotkeys panel.

## Local check

Open `index.html` directly in a browser, or serve this folder with any static server.
