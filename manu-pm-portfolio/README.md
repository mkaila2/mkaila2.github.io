# Manu Kaila — Product Management Portfolio

A minimal static portfolio for GitHub Pages. No npm, build steps, or dependencies.

## Customize BEFORE publishing
1. In `index.html`, replace `YOUR_EMAIL@example.com` with your email.
2. In `index.html`, replace `YOUR-LINKEDIN` in the LinkedIn URL with your actual public profile path.
3. Put your current resume PDF in `assets/` and name it `resume.pdf` (or edit the resume button's link). The PDF is deliberately not included because no verified PDF was provided.
4. Review all four case studies for factual accuracy and employer/client confidentiality; remove the editorial notes when you're happy with public copy.
5. Optionally adjust colors in `assets/style.css` under `:root`.

## Publish with GitHub Pages (no terminal needed)
1. On GitHub, create a new PUBLIC repository. Use `YOUR_USERNAME.github.io` for a root website URL, or `manu-portfolio` for a project site.
2. Choose **Add file → Upload files** and upload the CONTENTS of this folder (not the .zip). Preserve `assets/` and `projects/` directories. Commit the upload.
3. Go to **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, select **main**, select **/(root)**, and save.
5. Your URL will be `https://YOUR_USERNAME.github.io/` (if your repo is `YOUR_USERNAME.github.io`) or `https://YOUR_USERNAME.github.io/manu-portfolio/` (for a project repo).
6. It may take a few minutes to publish.

## Local preview
Double-click `index.html` in Finder. All links are relative, so navigating between case studies should work.

## Structure
- `index.html` — homepage, selected work, smaller projects, about, contact
- `projects/*.html` — four individual case studies
- `assets/style.css` — responsive design
- `assets/main.js` — copyright year
- `assets/resume.pdf` — add this yourself
