# Budget Tracker

A simple budget tracker. Switch a bill on when you pay it and the date is filled in for you.
Your budget is saved on your own device. Nothing is sent anywhere.

## Put it online with GitHub Pages (free)

1. On github.com, create a new repository (for example `budget-tracker`). Make it **Public**.
2. Upload these files to it: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two the page shows your address, `https://YOUR-USERNAME.github.io/budget-tracker/`.

## Install it on an iPhone

1. Open the address in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it from the new icon.

## Your own bills

This repository is public, so the app starts empty. Do **not** commit your real budget here.

To load your own items, save your private backup file (for example `my-budget-import.json`) to iCloud Drive or send it to your phone,
then open the app and tap **Restore**. Tap **Back up** now and then to keep a fresh copy.

## Notes

- Data lives in the browser on that device. A different phone or browser starts empty until you Restore a backup.
- Updating the app: edit and re-upload `index.html`. If a change doesn’t appear, close and reopen the app.
