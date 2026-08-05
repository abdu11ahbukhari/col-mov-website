# col-mov-website

Marketing site for **Collective Moves**, a senior-transition professional network in Dallas–Fort Worth.

Static HTML/CSS/JS. No build step, no dependencies. Open `index.html` in a browser to preview locally.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `team.html` | Meet the Collective |
| `resources.html` | Valuable Resources |

## Deploy to GitHub Pages

From inside this folder:

```bash
git init
git add -A
git commit -m "Collective Moves website"
git branch -M main
git remote add origin https://github.com/<your-username>/col-mov-website.git
git push -u origin main
```

Then in the repo on github.com: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.

The site goes live in about a minute at:

```
https://<your-username>.github.io/col-mov-website/
```

## Notes

- `.nojekyll` is included so GitHub Pages serves the files as-is.
- Book cover images load from the Open Library covers API. Any cover that fails to load falls back automatically to a typographic cover card, so nothing appears broken.
- Guide download buttons on the resources page are disabled until the PDFs exist. See `assets/guides/README.txt` for the filenames to add and how to switch a card to a live download.
- Valerie's "View Valerie's Listings" buttons link out to her Compass agent page.
