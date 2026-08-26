# Ananya Hegde — Portfolio

A single-page portfolio site, built with plain HTML/CSS/JS (no build step, no dependencies to install), ready to host on GitHub Pages for free.

**Files:**
- `index.html` — page structure & content
- `styles.css` — the "blueprint" visual design (built around your published dumbbell network topology)
- `script.js` — the animated packet diagram in the hero, plus scroll reveals

## Go live on GitHub Pages (takes ~5 minutes)

1. **Create a new repository** on GitHub.
   - Go to [github.com/new](https://github.com/new)
   - Name it whatever you like. If you want it at `https://ananyahegde058.github.io` directly, name the repo exactly `ananyahegde058.github.io`. Any other name works too — it'll just live at `https://ananyahegde058.github.io/<repo-name>`.
   - Set it to **Public**, and don't initialize with a README (you already have one).

2. **Upload these files.**
   - Easiest way: on the repo page, click **Add file → Upload files**, then drag in `index.html`, `styles.css`, `script.js`, and `README.md`. Commit directly to the `main` branch.
   - Or, from your computer, using git:
     ```bash
     git init
     git add index.html styles.css script.js README.md
     git commit -m "Initial portfolio"
     git branch -M main
     git remote add origin https://github.com/<your-username>/<repo-name>.git
     git push -u origin main
     ```

3. **Turn on GitHub Pages.**
   - In the repo, go to **Settings → Pages**.
   - Under "Build and deployment", set **Source** to `Deploy from a branch`.
   - Set **Branch** to `main` and folder to `/ (root)`. Click **Save**.

4. **Visit your site.**
   - GitHub will show a link at the top of that same Pages settings screen once it's built (usually within a minute or two) — something like `https://<your-username>.github.io/<repo-name>/`.
   - Re-uploading a file and committing automatically redeploys the site — no extra steps needed.

## Making changes later

Everything is plain text, so you can edit directly on GitHub (open a file → pencil icon → edit → commit) or clone the repo locally and edit in any code editor. There's no build/compile step — saving the file is the whole deploy.

Common tweaks:
- **Text/content** — edit the relevant section in `index.html`.
- **Colors** — edit the `:root` variables at the top of `styles.css` (e.g. `--accent` is the copper/rust highlight color).
- **Add a project** — copy one `<article class="card">…</article>` block under `#work` in `index.html` and edit its contents.

## Optional: custom domain

If you buy a domain later, add a `CNAME` file with just the domain name in it to the repo root, then point your domain's DNS to GitHub Pages per [GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
