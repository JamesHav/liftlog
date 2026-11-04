# Lift Log

A gym workout tracker that installs on your Android phone, works offline, keeps your data on the phone, and exports to Excel.

## Put it online (one time, about 15 minutes)

You need a free GitHub account: https://github.com/signup

1. Unzip `lift-log.zip` on your computer.
2. On GitHub, click **+** (top right), then **New repository**. Name it `lift-log`, keep it **Public**, and click **Create repository**.
3. On the next page, click **uploading an existing file**. Drag in everything from the unzipped folder (`index.html`, `manifest.webmanifest`, `sw.js`, `xlsx.full.min.js`, `README.md` and the `icons` folder), then click **Commit changes**.
4. Go to **Settings**, then **Pages** (left side). Under **Branch**, pick `main` and `/ (root)`, then click **Save**.
5. Wait a minute or two, refresh, and your link appears at the top, like `https://YOUR-NAME.github.io/lift-log/`.

## Install it on your phone

1. Open your link in **Chrome** on Android.
2. Tap **⋮**, then **Install app** (or **Add to Home screen**).
3. Open Lift Log from its new icon. From now on it works without internet.

## Your data

- Everything is saved on your phone only. Nobody else, GitHub included, can see it.
- Uninstalling the app or clearing Chrome’s site data deletes your log, so tap **Export to Excel** now and then as a backup. Files go to your Downloads folder.

## Making changes later

Edit the files, upload them to the repository again, and open `sw.js` to change `liftlog-v1` to `liftlog-v2` (and so on) so phones pick up the new version. Close and reopen the app twice to see the update.
