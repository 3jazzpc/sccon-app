# sccon-app

Live survey "Wem gehört die Zukunft?" – a single-file web app (`index.html`) with live results.

- **Frontend:** plain HTML/CSS/JS, no build step
- **Backend:** Firebase Firestore (Spark plan) for responses and tallies
- **Admin:** Firebase email/password login for export, delete and config
- **Hosting:** GitHub Pages

## Run locally

Open `index.html` in a browser, or serve it:

```sh
python3 -m http.server 8000
```

## Deploy

Push to `main`; GitHub Pages serves `index.html`.
