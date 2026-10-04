# Hamyon — landing page

One-page site for [Hamyon](https://github.com/YadgarovFayzullo/hamyon-landing), an iPhone app that reads bank SMS in Uzbekistan and turns them into a clean spending feed.

Plain HTML, CSS and a little JavaScript — no build step. Open `index.html` through any static server, e.g.:

```bash
python3 -m http.server 8765
```

then visit http://localhost:8765. The font (Bricolage Grotesque) loads from Google Fonts.

Preview parameters for checking scroll animations without scrolling: `?p=0…1` (first screen), `?burst=0…1` (bank logos), `?day=0…1` (notification stack).
