# Shark Week — GitHub Pages ready

Upload the **contents** of this folder to the root of a GitHub repository.

Included:
- Shark/ocean-themed iPhone UI
- Red TAMPON IN / green TAMPON OUT button
- Live timer
- Insertion timestamp
- Removal timestamp
- Session history
- Calendar view
- 8-hour in-app safety flag
- Local-only browser storage
- PWA manifest
- Offline service-worker cache
- iPhone Home Screen icon

## GitHub Pages
Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/(root)` → Save.

## iPhone
Open the published HTTPS URL in Safari → Share → Add to Home Screen → enable Open as Web App → Add.

## Notifications
This build intentionally keeps data local. A reliable background 8-hour push notification requires a push service; the app therefore shows the 8-hour flag when it is opened/returned to.
