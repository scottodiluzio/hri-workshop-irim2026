# I-RIM 3D 2026 HRI Workshop website

Static website ready for GitHub Pages.

## Files
- `index.html` — complete single-page workshop website
- `style.css` — responsive styling

## Publish with GitHub Pages — exact steps

1. Sign in to GitHub.
2. Click **+** in the top-right corner and choose **New repository**.
3. Repository name: `irim-hri-workshop`.
4. Set visibility to **Public**.
5. Do **not** add a README, .gitignore, or license during repository creation.
6. Click **Create repository**.
7. On the new repository page, click **uploading an existing file**.
8. Upload `index.html` and `style.css` from this folder.
9. Click **Commit changes**.
10. Open **Settings** in the repository.
11. In the left menu, open **Pages**.
12. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
13. Under **Branch**, choose `main` and folder `/(root)`.
14. Click **Save**.
15. Wait 1–3 minutes and refresh the Pages section. GitHub will show the public URL, normally:
    `https://YOUR-USERNAME.github.io/irim-hri-workshop/`
16. Open the URL and test the menu, EasyChair submission button, official I-RIM link, speaker links, and Google Maps venue link.

## Important content checks before announcing the site

- Confirm the workshop has been formally accepted and the date/time are final.
- Confirm whether workshop-specific extended abstracts should use the main I-RIM EasyChair Extended Abstract track or a dedicated workshop route.
- The site currently points to the official I-RIM 3D 2026 EasyChair system.
- The conference Extended Abstract deadline shown on the site is 4 October 2026, based on the current official I-RIM English call. Re-check it before public announcement because deadlines can change.
- Replace Francesco D'Orazio's initials placeholder with a speaker-approved headshot when available.
- The third invited speaker remains TBA, matching the workshop proposal.

## Replace Francesco D'Orazio's photo

1. Obtain a speaker-approved photo, ideally JPG or PNG.
2. Rename it `francesco-dorazio.jpg`.
3. Create a folder named `assets` in the repository and upload the image there.
4. In `index.html`, find:
   `<div class="speaker-photo placeholder-photo" ...>`
5. Replace that whole `<div>...</div>` with:
   `<img class="speaker-photo" src="assets/francesco-dorazio.jpg" alt="Francesco D'Orazio" />`
6. Commit the change. GitHub Pages redeploys automatically.

## Institutional logo note

The page references public institutional logo assets hosted by the respective organizations or project pages. For a long-lived production website, ask each institution for the approved logo file and usage permission, then store the approved files in a local `assets/` folder to avoid broken external image links.
