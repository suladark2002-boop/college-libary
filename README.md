# college-libary

A simple college library website project with a GitHub Pages-ready static layout.

## Project structure

- `college-library/index.html`
- `college-library/books.html`
- `college-library/contact.html`
- `college-library/style.css`
- `college-library/README.md`
- `.github/workflows/pages.yml`

## Local preview

```bash
cd college-library
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## GitHub Pages

The repository includes a Pages workflow that deploys the `college-library` folder automatically. Configure GitHub repository settings to use GitHub Actions as the Pages source.
