# Tyre Set Log

Offline phone app for logging tyre sets: inflation pressure (LHS/RHS), inflation and target temperature, and per corner (FL, FR, RL, RR) wear at 5 points, Shore at 3 points, surface temperature, weight and circumference. Exports to Excel (.xlsx) or CSV through the iPhone share sheet, so you can send it by Mail.

## Put it online with GitHub Pages
1. Create a free account at github.com and sign in.
2. Click **+ → New repository**. Name it `tyre-log`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in every file from this folder, including the `fonts` folder, then click **Commit changes**.
4. Go to **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
5. After a minute or two the page shows your address, like `https://YOUR-NAME.github.io/tyre-log/`.

## Install on the iPhone
1. Open that address in **Safari** (it must be Safari).
2. Tap **Share → Add to Home Screen → Add**.
3. Open it once from the Home Screen icon while you have signal. After that it works with no signal.

## Using it
- **+ New set** copies the last set's number (+1), pressures and temperatures. Use **Next** on the keypad to move through the fields.
- Everything saves on the phone as you type.
- **Excel** or **CSV** opens the share sheet. Pick **Mail**.
- **Backup:** data lives only on this phone. Safari can clear it if the app goes unused for several weeks, so export regularly. To restore, tap **import a CSV** on the home screen and pick a CSV this app exported.

## Updating the app
Upload the changed files to the repository, and change `VERSION` in `sw.js` (for example to `tyre-log-v2`). Open the app with signal twice and the new version loads.

Note: anyone with the address can open the app, but your measurements never leave your phone. They are not stored on GitHub.
