# ngphuc.exe Portfolio — GitHub Pages

## Publish the site

1. On GitHub, create a **public** repository named `ngphuc203.github.io` (the name must match your GitHub username exactly).
2. Upload `index.html` and the `assets` folder (including `logo.png`) to the repository's top level, then commit the upload to the `main` branch.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/(root)`, then save.
5. After the Pages deployment finishes, open `https://ngphuc203.github.io`. Enable **Enforce HTTPS** in Settings → Pages when it is available.

Keep `index.html` beside `assets/logo.png`; the page references the logo with the relative path `assets/logo.png`. To publish later edits, commit the changed files to `main` again.

## Interactive experience

The portfolio presents ngphuc.exe as a web designer and full-stack developer focused on frontend and backend development, API integrations, and practical AI. It includes a design-to-development workflow, four capability areas, and a filterable 3D project showcase: nine labeled slats orbit clockwise around a circular ring while the selected project is revealed from the center outward. Visitors can drag the ring, select a slat, and search or filter projects. The hero includes a three-slide carousel and a typing animation for web design, frontend/backend, and API/AI roles. The background uses a Three.js particle universe with a lightweight canvas fallback when WebGL is unavailable. On desktop, the full 3D universe rotates toward the pointer with eased follow, independently drifting particle layers, cursor-following light, and camera parallax. The chrome `ngphuc.exe` logo has orbiting accents, the avatar and hero panel respond to the pointer, and vertical technical data rails animate behind the project showcase. Motion respects the visitor's reduced-motion preference; project rotation pauses while hovered, focused, or outside the viewport. The contact form prepares a message in the visitor's default email app; it does not send anything automatically.

GitHub Pages provides static hosting while the repository, account, and Pages eligibility remain active; it is not a perpetual hosting guarantee. With GitHub Free for a personal account, the source repository needs to be public. Anyone can view the published site.