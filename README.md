# Personal Website

A simple, responsive personal portfolio site, ready to publish with GitHub Pages. No build tools or dependencies required.

## Customize

1. Open `index.html` and replace `Your Name`, the biography, education, work experience, research papers, project descriptions, and placeholder URLs.
2. Add your photograph to `assets/` (for example `profile.jpg`) and change the image `src` in `index.html` to `assets/profile.jpg`. Update the image alt text.
3. Adjust colors and typography in `styles.css` if desired.
4. Open `index.html` in a browser to preview.

## Publish on GitHub Pages

1. Create a new repository on GitHub, e.g. `personal-website` (or `YOUR_USERNAME.github.io` for a root personal site).
2. In this folder, run:

   ```bash
   git init
   git add .
   git commit -m "Initial personal website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages** and choose **Deploy from a branch**, branch **main**, folder **/(root)**. Save.
4. Your site will be available at `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/` (or `https://YOUR_USERNAME.github.io/` for the root personal site).

## Structure

```text
personal-website/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── profile-placeholder.svg
├── .gitignore
└── README.md
```
