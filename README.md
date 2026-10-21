# repcast-tv-landing-page

The website for [RepCast](https://github.com/Mallikarjuntr/repcast-tv-app), a Fire TV fitness coach: what it is, how to set up the phone, the privacy policy and the terms of use. Live at https://repcast.netlify.app/ (Netlify deploys the `main` branch).

Plain HTML and CSS, no build step. To preview locally, serve the folder with any static server, for example:

```bash
npx --yes serve .
```

- `index.html` — home page
- `privacy.html` (also `/privacy`) — privacy policy
- `terms.html` (also `/terms`) — terms of use
- `assets/site.css` — the "Studio" look shared with the TV app
- `assets/fonts/` — Barlow and Barlow Semi Condensed, self-hosted (SIL Open Font License, see `OFL.txt`)
- `netlify.toml` — publish settings and security headers; `/camera/` serves the phone camera page (built and published by repcast-tv-app on GitHub Pages, proxied here), and `/go?code=…`, which the TV's QR code opens, forwards to it
