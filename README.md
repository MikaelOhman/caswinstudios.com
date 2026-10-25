# caswinstudios.com

The CasWin Studios website: plain HTML and CSS, no build step. Hosted on GitHub Pages with the custom domain in `CNAME`.

- `index.html`: home (games, about us, contact)
- `driftwood/`: the Driftwood page, and `driftwood/privacy/` (the privacy policy linked from Google Play)
- `privacy/`: the website's own privacy note
- `saltmere/wiki/`: the Saltmere wiki. Made by `tools/make_wiki.py` in the Saltmere repository from the game's own data (run `godot --headless --path . -s tools/wiki_data.gd` there first), so edit it there, not here. Story secrets sit in spoiler boxes that ask before they open.
- `img/`: images (made from the game's store art and the logo)

Preview locally: open `index.html` in a browser, or run `python -m http.server` here and visit http://localhost:8000.
