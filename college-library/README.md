# Campus Library Website

This project is a simple static library website for a college campus. It contains:

- `index.html` — home page
- `books.html` — catalog page
- `contact.html` — contact and support page
- `style.css` — shared styling for the entire site

## Local preview

Open the `index.html` file directly in a browser, or run a local server from this folder:

```bash
cd college-library
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages deployment

This site is ready to deploy to GitHub Pages as a static site. The easiest option is to use a GitHub Actions workflow that publishes the `college-library` folder.

1. Push this repository to GitHub.
2. Go to the repository's Settings → Pages.
3. Set the source to GitHub Actions.
4. The included workflow file in `.github/workflows/pages.yml` will deploy the site automatically.

After deployment, GitHub Pages will publish the site at a URL like:

`https://<your-username>.github.io/<repository-name>/`

## Notes

The design is mobile-friendly, uses pure HTML and CSS, and does not require any external dependencies.
