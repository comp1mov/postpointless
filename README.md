# post.pointless Vercel Preview

Deploy root for the current post.pointless baseline.

Source snapshot:

`../pointcloud-viewer-v0_98_share_release.html`

Preview entry:

`index.html`

Public release URL:

https://postpointless.vercel.app/

Vercel dashboard:

https://vercel.com/gregtsv23-6635s-projects/postpointless

Vercel project:

`postpointless`

GitHub repository:

https://github.com/comp1mov/postpointless.git

## Notes

- This folder is intentionally small and static.
- Do not deploy the whole `PointClouds` workspace.
- Point cloud files are loaded by the browser from the user's local file picker.
- The app imports Three.js and Tweakpane from CDN import maps.
- Default export output is `Screen / Current View`, so image and video capture should keep the current viewport aspect.
- `Rec with UI Button` can turn the white UI dot into a quick record start/stop control.
- `Controls -> Help` and the `?` button next to the title open the help/hotkeys panel.
- Project domain is `postpointless.vercel.app`; old `vercel-preview-lime.vercel.app` project domain was removed.
- The Vercel project is connected to GitHub repository `comp1mov/postpointless` on production branch `main`.

## Local check

Open `index.html` directly in a browser, or serve this folder with any static server.
