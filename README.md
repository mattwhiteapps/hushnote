# Hushnote website

Support page and privacy policy for the Hushnote iPhone app, ready for GitHub Pages.

## Publishing

1. Create a public repository on GitHub, for example `hushnote`.
2. Upload everything in this folder to the root of the repository (Add file › Upload files, then drag the files in).
3. In the repository, open Settings › Pages. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-github-name>.github.io/hushnote/`.

The two links App Store Connect needs:

- Privacy Policy URL: `https://<your-github-name>.github.io/hushnote/privacy.html`
- Support URL: `https://<your-github-name>.github.io/hushnote/`

## Files

- `index.html`: support page with contact details and common questions
- `privacy.html`: privacy policy
- `style.css`: shared styles, light and dark mode
- `icon.png`, `favicon.png`, `apple-touch-icon.png`: app icon at web sizes
- `.nojekyll`: tells GitHub Pages to serve the files as they are
