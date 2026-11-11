# Siseri Ajiri — Reference-Matched Website

This version recreates the supplied reference as the website's main hero: a black textured tilted card, large white stacked headline, red right-side panel, red asterisk and dramatic studio lighting.

## Live sites

- Netlify: https://siseri-ajiri-website.netlify.app/
- GitHub Pages: https://siseriajiri.github.io/siseri-ajiri-website/

Netlify is the primary hosting site. The current version was deployed from this folder with the Netlify CLI. To publish changes to Netlify, run:

```sh
npx netlify-cli deploy --prod --dir . --no-build
```

GitHub Pages remains enabled as a second live copy and automatically redeploys when changes are pushed to `main`.

## Files
- `index.html`
- `style.css`
- `script.js`

Open `index.html` in a browser. The hero is responsive and the three service labels link to the matching service descriptions below.

The site uses Google Fonts (Manrope) when online. The visual grain and studio lighting are created in CSS.
