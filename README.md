# Shark Week — Installable iPhone Web App

This is the no-Mac version of Shark Week. It is a Progressive Web App (PWA), so it can be added to an iPhone Home Screen and opened like an app.

## What it does

- Big red/green tampon IN/OUT button
- Timer begins when marked IN
- Exact inserted and removed timestamps
- Completed-session history
- Data saved locally in the browser on the device
- Offline cache after first successful load
- Shark-themed icon and ocean styling

## Important: hosting is required

iPhone web apps need to be opened from a web address. A ZIP file itself cannot be installed as an iPhone Home Screen web app.

Upload this folder to any static HTTPS host (for example GitHub Pages, Cloudflare Pages, Netlify, or another static web host). No server/database is needed.

## Install on iPhone

1. Open the hosted Shark Week URL in Safari.
2. Tap Share.
3. Tap **Add to Home Screen**.
4. Turn on **Open as Web App** if shown.
5. Tap **Add**.

Apple documents this exact Home Screen web-app flow here:
https://support.apple.com/guide/iphone/iphea86e5236/ios

## Privacy

The app uses `localStorage` only. There is no login, analytics, or backend in this package.

## Medical note

This app is a tracker, not medical advice. If you are concerned about tampon use or symptoms, follow the product instructions and seek medical advice when appropriate.
