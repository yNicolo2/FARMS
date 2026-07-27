# yNicolo — Example Website

Files created for a static showcase site:

- `index.html` — main page.
- `css/style.css` — styles.
- `js/main.js` — behavior (accordion, smooth scroll).
- `images/placeholder.svg` — sample preview image.
- `manifest.json` — simple web manifest.

To view the site, open `site/index.html` in your browser or serve the folder with a static server:

```bash
# from the schematics folder
python -m http.server 8000 --directory site
# then open http://localhost:8000
```
Added features:

- Dark/light theme toggle (moon/sun button)
- Animated cards and modal interactions
- Clean modern farm showcase with clear CTA
- Interactive `Charcoal Farm — 4M / hour` panel with download buttons (placeholders)

Relevant files:

- `site/images/icons/sun.svg` and `moon.svg` — theme icons
- `site/downloads/charcoal-farm.schematic` — placeholder schematic
- `site/downloads/charcoal-farm-world.zip` — placeholder world zip

Testing notes:

- Buttons now open functional modals. Downloads are placeholders in `site/downloads/`.
- The sign-in form shows a notification message and is marked as coming soon.
- Sounds are disabled for a cleaner UI.

If you want me to replace placeholders with real assets, update the color palette, or add actual schematic/world downloads, just say so.
