# Due Bill 🧾

**Due Bill** is a simple, private, offline-first mobile app for tracking what you owe at your local shops — tea stalls, grocery stores, coffee shops, anywhere you run a tab. Built with React Native (Expo), with all data stored locally on-device.

This repo contains both the **mobile app** and its **marketing landing page**.

## [Visit For download APK](https://jahid757.github.io/baki-apk)

---

## ✨ Features

- 🏪 **Multiple shops** — track dues separately for every shop you visit
- ⚡ **One-tap purchases** — save your usual items (tea, coffee, groceries) as quick-add buttons with preset prices
- 💳 **Flexible payments** — pay in full or make partial payments to reduce a due
- 🔔 **Due limit alerts** — set a warning limit per shop (or a global default) and get a local notification when you're close to or over it
- 📝 **Notes on transactions** — attach a note to any entry, e.g. "borrowed for a friend"
- 🔍 **Search** — quickly find a shop or a past transaction across your whole history
- 📊 **Spending overview** — see total dues, and how much you've spent this week/month
- 🔒 **Fully private** — no account, no server, no internet required. All data lives in `AsyncStorage` on your device.

## 🌐 Landing page

`index.html` is a single, self-contained HTML file (no build step, no dependencies) — the banner image is embedded as base64, so you can host it anywhere: GitHub Pages, Netlify, Vercel, or any static file host.

Before publishing, update the download button links inside the file:

```html
<a class="btn-download" href="./Baki.apk" download="Baki.apk">
```

Replace `Baki.apk` with a permanent link to your built APK — e.g. a GitHub Release asset URL.

### Deploying to GitHub Pages

```bash
# from the repo root
git add index.html
git commit -m "Add landing page"
git push
```

Then in **Settings → Pages**, set the source to the branch/folder containing `due-bill-landing.html` (or rename it to `index.html` in a `docs/` folder for the simplest setup).

---

## 🗺️ Roadmap ideas

- [ ] Backup & restore (export/import all data as a file)
- [ ] App lock (PIN/biometric)
- [ ] Spending categories across shops
- [ ] Light theme toggle
- [ ] Multi-currency support

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<p align="center">Made for shopkeepers &amp; shoppers who are tired of forgetting who owes what. 🫖</p>