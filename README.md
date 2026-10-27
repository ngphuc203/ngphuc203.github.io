# ngphuc Portfolio — GitHub Pages

## Publish the site

1. On GitHub, create a **public** repository named `ngphuc203.github.io` (the name must match your GitHub username exactly).
2. Extract this ZIP. Upload `index.html`, the `assets` folder (including `logo.jpg`), and `.nojekyll` to the repository's top level, then commit the upload to the `main` branch.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/(root)`, then save.
5. After the Pages deployment finishes, open `https://ngphuc203.github.io`. Enable **Enforce HTTPS** in Settings → Pages when it is available.

Keep `index.html` beside `assets/logo.jpg`; the page references the logo with the relative path `assets/logo.jpg`. To publish later edits, commit the changed files to `main` again.

GitHub Pages provides static hosting while the repository, account, and Pages eligibility remain active; it is not a perpetual hosting guarantee. With GitHub Free for a personal account, the source repository needs to be public. Anyone can view the published site. The current contact form is a front-end demonstration and does not deliver submissions to email; connect a form service or backend before relying on it.