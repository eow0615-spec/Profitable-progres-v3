# Profitable Progress: put it on your phone with GitHub

These 5 files make an installable app (a PWA). Once it is on GitHub Pages, you open it on your Samsung S24 FE in Chrome and add it to your home screen. It then opens full screen like a normal app and works offline.

Files to upload (all in the same folder, no subfolders):
- index.html  (the whole app)
- manifest.json  (app name, colors, icons)
- sw.js  (lets it work offline)
- icon-192.png and icon-512.png  (the app icon)

## Step 1: Make the repository
1. Go to github.com and sign in (or create a free account).
2. Tap the + at the top, then New repository.
3. Name it profitable-progress, choose Public, and tap Create repository.

## Step 2: Upload the files
1. On the new repository page, tap "uploading an existing file".
2. Drag in all 5 files (or tap "choose your files").
3. Tap Commit changes.

## Step 3: Turn on GitHub Pages
1. Open the repository's Settings, then Pages.
2. Under Build and deployment, set Source to "Deploy from a branch".
3. Set Branch to main and the folder to / (root), then tap Save.
4. Wait 1 to 3 minutes and refresh. A link appears: https://YOUR-USERNAME.github.io/profitable-progress/

## Step 4: Install it on your phone
1. Open that link in Chrome on your S24 FE.
2. Tap the three dots menu, then "Add to Home screen" (or "Install app").
3. Tap Install. The gold P icon appears on your home screen.

## Updating the app later
Upload the changed file with the same name (Add file, then Upload files) and commit. Open the app while online, close it fully, and open it again to get the new version.

## Good to know
- Your workouts, calories, streaks and settings are saved on the phone only. Clearing Chrome's site data for the app erases them.
- Alarms and reminders in this version are previews. A web app cannot ring an alarm or send a reminder when it is closed. Real alarms need the native Android version.
- The camera button is a mock-up for now. Barcode scanning is not built yet.
- Calorie numbers and food values are estimates, not medical advice. Day trading and investing lessons are for practice and education, and trading can lose money.
- GitHub Pages on a free account needs the repository to be public, so do not put private information in these files.
