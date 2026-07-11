# Georlia Sgouraki — Portfolio

A simple, fast personal portfolio site: home (hero + projects) and an about page.

## Files
- `index.html` — home page (hero + projects)
- `about.html` — about page
- `style.css` — all styling
- `script.js` — mobile nav menu toggle
- `images/` — SVG illustrations (placeholders — see note below)

## Publish it on GitHub Pages

1. Create a new repository on GitHub.
   - If you want it at `https://yourusername.github.io`, name the repo exactly `yourusername.github.io`.
   - Otherwise any repo name works — it'll be published at `https://yourusername.github.io/repo-name`.
2. Upload all these files to the root of that repo (drag-and-drop on GitHub works fine, or use git).
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
5. Wait a minute or two — GitHub will give you the live URL at the top of that Pages settings screen.

## About the illustrations

The illustrations in `images/` (graduation cap graphic, pet shop scene, medical/NGO graphic, about-page circle) are original SVGs I made to match your Figma's color palette and composition, since I can't copy the exact stock illustrations from your file. If you'd like the real ones:

1. In Figma, select each illustration → right-click → **Export** → choose SVG or PNG.
2. Save it into the `images/` folder with the same filename it's replacing (e.g. `project-graduate.svg`), or update the `src` in `index.html` / `about.html` to point to your new file.

## Things you'll probably want to personalize
- Swap the `#` placeholder links on "View Project" buttons to your real project links.
- Update the LinkedIn, email, and GitHub links in the footer.
- Add a real `resume.pdf` to the repo and point the "Resume" button on the about page to it.
