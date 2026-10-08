# Xiaokun Wu — Academic Website

A static personal website (plain HTML + CSS, no build step).

- `index.html` — all content
- `styles.css` — design (light/dark mode, responsive)
- `assets/photo.jpg` — headshot (square, 640×640; replace the file to change it)

## To finish before going live

1. **Links** — in `index.html`, uncomment the Google Scholar / LinkedIn / SSRN lines in the sidebar and fill in the URLs.
2. **Job market paper** — optionally add an abstract and a PDF link
   (there is a commented-out template inside the "Job Market Paper" block).

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)`.
3. The site appears at `https://<username>.github.io/xw-website/`.
   For a cleaner URL, name the repo `<username>.github.io` or add a custom domain.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
