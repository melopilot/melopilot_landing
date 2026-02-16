# MeloPilot Landing Page

Landing page for **MeloPilot** — learning apps: Piano Pilot, Guitar Pilot, Singing, English Pilot, and more.

## Deploy on GitHub Pages (free)

1. **Push this repo to GitHub**
   - Create a new repository on GitHub (e.g. `melopilot_landing` or `melopilot.github.io`).
   - From this folder:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git add .
   git commit -m "Add MeloPilot landing page"
   git push -u origin main
   ```

2. **Turn on GitHub Pages**
   - Open your repo on GitHub → **Settings** → **Pages**.
   - Under **Source**, choose **Deploy from a branch**.
   - Branch: **main** (or **master**), folder: **/ (root)**.
   - Save.

3. **Your site will be live at**
   - `https://YOUR_USERNAME.github.io/YOUR_REPO/`  
   - Or, if the repo is named `YOUR_USERNAME.github.io`, at `https://YOUR_USERNAME.github.io/`.

No build step needed — plain HTML and CSS.

## Local preview

Open `index.html` in a browser, or use a simple server:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Structure

- `index.html` — single-page layout (hero, apps, about, CTA, footer)
- `styles.css` — typography, layout, and theme
