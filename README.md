# Justin Villavicencio — Portfolio

Static one-page portfolio site. No build step — plain HTML/CSS/JS.

```
index.html      Page content
css/style.css   All styling (dark, bold/modern theme — indigo accent)
js/main.js      Mobile nav toggle, scroll-reveal, footer year
assets/         Local images (headshot not yet wired into the page)
```

## Preview locally

Open `index.html` directly in a browser, or serve it:

```
npx serve .
```

## Deploy

Live site is deployed on Netlify from this repo. To push a manual deploy:

```
npx netlify-cli deploy --prod --dir=.
```

To wire up auto-deploy on every `git push`, connect this GitHub repo to the Netlify site once from the Netlify dashboard (Site settings → Build & deploy → Link repository).

## To do

- Swap in a real headshot in `assets/` and reference it in the hero section of `index.html`.
