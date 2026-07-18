# Setting this up as your GitHub Pages site

1. Create a new repository on GitHub named **exactly** `Nidita.github.io` (must match your GitHub username, case doesn't matter but the format does).
2. Upload every file in this folder to the **root** of that repo — `index.html`, `research.html`, `publications.html`, `projects.html`, `teaching.html`, `contact.html`, and the `css/` and `assets/` folders. Keep the folder structure exactly as it is; don't put them inside a subfolder.
3. Go to the repo's **Settings → Pages**. Under "Build and deployment," source should already default to "Deploy from a branch," branch `main`, folder `/ (root)`. Save if it wasn't already set.
4. Wait 1–2 minutes, then visit `https://nidita.github.io` — it should be live.
5. **Before it's ready to share with professors:**
   - Add a real headshot: drop a photo at `assets/headshot.jpg`, then in `index.html` replace the `<div class="avatar-mark">NR</div>` block with `<img src="assets/headshot.jpg" alt="Nidita Roy" style="width:100%;border-radius:3px;">`
   - Add your CV: drop the PDF at `assets/Nidita_Roy_CV.pdf` (the Download CV button on the Contact page already points here)
   - Search each page for `placeholder-note` — those little dashed-border notes mark everything still needing your confirmation (exact venue names, author orders, dataset details). Delete the note once you've filled in the real content next to it.
   - Every research fact on this site was carried over from the strategy document we built earlier — cross-check anything you're unsure of against that doc before publishing.

## Making changes later

Just edit the relevant `.html` file directly (or ask me to) and push the change — GitHub Pages rebuilds automatically within a minute or two of any push to `main`. No build step, no dependencies, nothing to install.
