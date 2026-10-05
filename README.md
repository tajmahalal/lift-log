# Lift Log

A personal workout and protein tracker that runs offline on an iPhone. All data stays on the phone.

## Put it on your iPhone (free, with GitHub Pages)

1. Make a free account at https://github.com/signup
2. Make a new **public** repository at https://github.com/new and name it `lift-log`.
3. On the new repo page, click **uploading an existing file**, then drag in every file from this folder and click **Commit changes**.
4. Open **Settings → Pages**. Under "Branch", choose `main` and `/ (root)`, then click **Save**.
5. Wait about a minute. Your app is at `https://YOUR-USERNAME.github.io/lift-log/`
6. On your iPhone, open that link in **Safari**, tap **Share → Add to Home Screen**, and keep **Open as Web App** on.
7. Open it once from the home screen while you're online. After that it works offline.

## Updating the app later

1. Upload the changed files to the repo again.
2. In `sw.js`, bump the version number (e.g. `liftlog-v21` → `liftlog-v22`) so the phone picks up the new version.
3. Open the app on your phone while you're online, then close and reopen it.

## Backups

The app stores data only on your phone. Use **Settings → Export backup** now and then and save the file to Files or iCloud Drive.
