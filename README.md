# BMW 530i — landing page

Static landing page for a private car sale. Pure HTML/CSS/JS, no build step.

## Files

- `index.html` — markup
- `styles.css` — styles (loft minimalism, creamy palette)
- `config.js` — **all editable text** (price, specs, features, description, photos)
- `images/` — car photos

## Edit content

Open `config.js`. Every text on the page lives there as a flat string.
Specs and features are simple arrays — add/remove lines freely.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy on GitHub Pages

1. Push this directory to a GitHub repo.
2. Repo → **Settings → Pages**.
3. **Source**: `Deploy from a branch`.
4. **Branch**: `main`, folder `/ (root)`. Save.
5. Wait ~30 sec. The site appears at `https://<username>.github.io/<repo>/`.

The included `.nojekyll` file disables Jekyll processing.
