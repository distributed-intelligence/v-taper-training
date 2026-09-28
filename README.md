# V / FORM — Weekly Training

Original HTML, CSS and JavaScript from your hosted V-taper training site.
These three files are copied unchanged from the original source repository.
No npm packages, build step, API keys or backend are required.

## Run locally

From this folder, run:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. Stop the server with Ctrl+C.

## Self-host

Copy index.html, style.css and app.js to any static web server's document root.
Keep all three together. The site also supports being served from a subfolder.

YouTube embeds and Google Fonts need internet access. Fonts have local fallbacks.
Workout set checks are held in memory and reset when the page reloads, as in the
original site. There is no database or ChatGPT login requirement in this code.

## Edit

- index.html: page structure and text
- style.css: colors, typography and responsive layout
- app.js: workout schedule, exercises, video IDs and interactions

Source commit: b10733c4764de8810e33ee8f05766bc6363ccb2a
