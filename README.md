# spotter-tv-landing-page

The website for [Spotter](https://github.com/Mallikarjuntr/spotter-tv-app), a Fire TV fitness coach: what it is, how to set up the phone, the privacy policy and the terms of use. Live at https://spotter-tv.netlify.app/ (Netlify deploys the `main` branch).

Plain HTML and CSS, no build step. To preview locally, serve the folder with any static server, for example:

```bash
npx --yes serve .
```

- `index.html` — home page
- `privacy.html` (also `/privacy`) — privacy policy
- `terms.html` (also `/terms`) — terms of use
- `assets/site.css` — the "Studio" look shared with the TV app
- `assets/fonts/` — Archivo and Archivo Narrow, self-hosted (SIL Open Font License, see `OFL.txt`)
- `netlify.toml` — publish settings and security headers
