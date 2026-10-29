# Chouaibou Toure

A simple personal introduction website built with plain HTML and CSS.

## Files

- `index.html` contains the page content.
- `style.css` contains the layout, colors, and responsive styles.
- `images/profile.jpg` is a photo of Mount Hombori, Mali, used in the profile section.
- `images/festival-segou.jpg` is a photo from the Festival sur le Niger in Ségou.
- `images/mount-fuji.jpg` is the Mount Fuji background photo.

The Mount Fuji background photo is CC0. The Mount Hombori photo is licensed under CC BY 2.0, and the festival photo is licensed under CC BY-SA 4.0. Their credits and source links are in the page; keep them if you reuse those images.

To personalize the contact link, replace `your-username` in the GitHub URL near the bottom of `index.html` with your GitHub username.

## Preview locally

1. The two referenced photos are already in the `images` folder.
2. Open `index.html` directly in a browser, or start a local server from this folder with `python3 -m http.server 8000`.
3. If you started the server, visit `http://localhost:8000`. Stop it with `Ctrl+C` when finished.
4. Resize the browser or open the page on a phone to check the mobile layout.

## Publish with GitHub Pages

1. Create a GitHub repository and add these files, including both images.
2. Push the files to the repository's `main` branch.
3. On GitHub, open the repository's **Settings**, then **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/(root)` folder, then select **Save**.
6. Wait for the Pages deployment to finish. The site URL will appear in the Pages settings; it usually looks like `https://your-username.github.io/repository-name/`.

If the page or images do not appear immediately, wait a minute and reload the published URL. GitHub Pages serves the files as static content; no framework or build step is needed.