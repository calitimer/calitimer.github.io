# CALI TIMER v1.6 — Installable iPhone PWA

Includes the v1.5 workout app plus home-screen icon, fullscreen standalone display, web app manifest and offline caching.

## Deploy on GitHub Pages
Upload **all seven files** in this folder to the root of the repository `calitimer/calitimer.github.io` (or your current Pages repository), then enable Pages from `main` / `(root)`.

## Install on iPhone
1. Open the live website in **Safari** (not the GitHub app or an in-app browser).
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Launch CALI TIMER using the new home screen icon.

## Data migration warning
Workouts and notes use localStorage and are tied to the website origin and sometimes the standalone app's storage container. Before changing domains or switching from Safari to the home-screen app, export a backup from the existing app. Open the installed app and import the backup. Verify notes and history before deleting anything.

## Limitations
Offline use works after the site has loaded and cached successfully at least once online. Browser storage may be cleared by the operating system, so keep JSON backups. iOS may pause JavaScript timers and audio when the screen locks; PWA installation does not guarantee background audio. This is not an App Store app.

