# Lindsey Liu Personal Website

Static personal academic website designed for GitHub Pages.

## Local Preview

Open `index.html` directly in a browser, or run a small local server from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages Deployment

1. Create a GitHub repository for the site.
2. Push this folder to the repository.
3. In GitHub, open `Settings` -> `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select the `main` branch and `/ (root)` folder.
6. Save. GitHub will publish the site after the Pages build finishes.

For a user site, name the repository `<github-username>.github.io`.
