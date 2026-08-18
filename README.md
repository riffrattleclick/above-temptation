# Above Temptation — Landing Page

Small static landing page for the short film "Above Temptation" (shot on 16mm).

What’s included
- `index.html` — the site HTML
- `styles.css` — styles for the site
- `CNAME` — (optional) contains the custom domain if you want to use GitHub Pages with a custom domain

Quick local preview
1. Clone the repository:
   git clone git@github.com:riffrattleclick/above-temptation.git
2. Open `index.html` in your browser, or run a simple static server, for example with Python 3:
   python -m http.server 8000
   then open http://localhost:8000

Customize
- Poster: replace `poster.jpg` with your poster image, or update the `img` src in `index.html` to point to a hosted image.
- Trailer: add your YouTube/Vimeo embed by replacing the commented iframe in `index.html`.
- Credits/festivals: edit the placeholders in `index.html`.

Deploying
- This site is static and works with GitHub Pages, Netlify, Vercel, or any static host. See the host's documentation for publishing and custom domain setup.

Notes
- This repository is intentionally minimal. Keep any sensitive or private configuration (screener links, passwords, access tokens) out of the public repo.

