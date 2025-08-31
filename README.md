# Mohsin Portfolio (GitHub Pages)

## How to publish
1. Create a new repository on GitHub, e.g. `mohsin-portfolio`.
2. Upload the contents of this folder (index.html, resume.pdf, assets/, .nojekyll).
3. In the repository, go to **Settings → Pages** and set **Source** to **Deploy from a branch**, then pick `main` and `/ (root)`.
4. Wait for the green **GitHub Pages** banner; your site will be at `https://<your-username>.github.io/<your-repo>/`.
5. Edit `index.html` and replace `https://<your-username>.github.io/<your-repo>` in the `<link rel="canonical">` and `og:url` tags with your real URL.
6. If you later use a custom domain, add a `CNAME` file at the repo root containing only your domain name.

## Files
- `index.html` — your portfolio page
- `resume.pdf` — your CV
- `assets/profile.jpg` — your photo
- `.nojekyll` — disables Jekyll processing on GitHub Pages
