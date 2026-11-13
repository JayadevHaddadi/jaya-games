# Jaya Games website

Static site for Jaya Games, an independent publisher of Jayadev Haddadi's board games. Plain HTML and CSS, no build step. Served by GitHub Pages from the `main` branch root: https://jayadevhaddadi.github.io/jaya-games/

## Layout
- `index.html` home page with game cards and about/contact
- `games/<game>.html` one page per game
- `style.css` shared styles (light and dark via `prefers-color-scheme`)
- `img/` web-sized images (webp, under 300 KB each)
- `favicon.svg`, `.nojekyll`

## Update
1. Edit the HTML/CSS, or copy `games/riverbend.html` for a new game and add a card in `index.html`.
2. Keep images under about 300 KB (webp).
3. Commit and push to `main`; Pages rebuilds in about a minute.
