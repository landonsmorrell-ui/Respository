# DRIFT: Escape the Abyss (Mobile)

A mobile-friendly 3D sailing survival game, ready for GitHub Pages.

## Publish with GitHub Pages

1. Create a **public** repository at https://github.com/new (for example `drift-game`).
2. Upload `index.html`, `.nojekyll`, and `README.md` to the **root** of the repository. You can extract the ZIP first and upload the files, not the enclosing folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, and click **Save**.
6. After deployment, open `https://YOUR-USERNAME.github.io/drift-game/`.
7. Share that URL by iMessage. Friends tap it to play in their phone browser.

If your repository is named `YOUR-USERNAME.github.io`, the URL is `https://YOUR-USERNAME.github.io/`.

## Notes

- The game loads Three.js from jsDelivr, so players need internet access.
- iMessage displays a link; the game opens in the phone browser rather than running inside the Messages bubble.
- High scores are stored locally per browser/device, not shared between players.
- Test on a phone after publishing. This package has not been physically tested on iOS or Android.
