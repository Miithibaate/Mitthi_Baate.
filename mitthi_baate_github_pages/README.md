
# Mitthi Baate — Static Website (GitHub Pages)

This folder contains a static website ready to upload to GitHub and host via GitHub Pages.

## What is included
- `index.html` — main homepage
- `style.css` — site styles
- `images/` — logo, price list, products images, and placeholders for flavors

## How to publish on GitHub Pages (step-by-step)

### Option A — Using Git (recommended)
1. Create a new GitHub repository (e.g. `mitthi-baate`).
2. On your computer, open a terminal and run:
   ```bash
   cd path/to/this/folder/mitthi_baate_github_pages
   git init
   git add .
   git commit -m "Initial site upload"
   git branch -M main
   git remote add origin https://github.com/Miithibaate/Mitthi_Baate..git
   git push -u origin main
   ```
3. In GitHub, go to your repository's **Settings → Pages**.
   - Under "Build and deployment", choose **Deploy from a branch**.
   - Branch: `main` and Folder: `/ (root)` then Save.
4. Wait a minute — your site will be published at:
   `https://<YOUR_USERNAME>.github.io/<REPO_NAME>/`

### Option B — Upload via GitHub web UI (no terminal)
1. Create a new repository on GitHub.
2. Click **Add file → Upload files**, upload all files and the `images/` folder, and commit.
3. Follow Step 3 from Option A to enable Pages.

## Replace images
- To use your real product photos, overwrite the files in `images/` with the same filenames:
  - `classic.jpg`, `dark.jpg`, `milk.jpg`, `crackle.jpg`, `butterscotch.jpg`, `dryfruit.jpg`, `special.jpg`
- Replace `images/logo.png` with your logo file (keep the same name).

## Test locally
- Open `index.html` in your browser directly (double-click file) to preview before uploading.

## Need help?
Reply here and I can:
- Customize layout or wording
- Create higher-quality product thumbnails from your grid
- Wire up an order form or email link
