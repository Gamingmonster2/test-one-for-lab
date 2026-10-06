# Test

A small, self-contained demo page that says **مرحبا** (*Hello*) in 26 languages,
beginning with **Arabic**, with the background cycling through three colour
themes every **10 seconds**.

This folder is an independent project. It has no build step and no dependencies —
it is just one `index.html` file.

## Files

```
test-one-for-lab/
└── index.html   # the whole site (HTML + CSS + JS in one file)
```

## Greetings included

Arabic, English, Spanish, French, German, Italian, Portuguese, Russian, Chinese,
Japanese, Korean, Hindi, Bengali, Urdu, Turkish, Persian, Hebrew, Greek, Dutch,
Swedish, Polish, Indonesian, Swahili, Ukrainian, Vietnamese, Thai.

## Run locally

Just open `index.html` in any modern browser, or serve the folder:

```bash
npx serve .
```

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, go to **Settings → Pages** and set the source to the
   `main` branch (root).
3. GitHub will serve the site at `https://<user>.github.io/<repo>/`.

## Use it as a labs.ly subdomain

Once the page is live, add one entry file to the labs.ly repository so the
subdomain points to it:

```json
// cnames/test.json
{ "target": "https://<user>.github.io/<repo>/" }
```

After that, `test.labs.ly` will serve this page.
