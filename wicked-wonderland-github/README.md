# Wicked Wonderland – Detective’s Casebook

A phone-friendly casebook for the Wicked Wonderland Mystery Night at the Roanoke County Public Library.
It works with no Wi-Fi or cell service once it has been added to your home screen.

## Put it on GitHub Pages
1. Create a new public repository (for example `wicked-wonderland`).
2. Upload all files in this folder to the repository’s main branch.
3. Go to **Settings → Pages**, set the source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute or two the app is live at `https://<your-username>.github.io/wicked-wonderland/`.

## Install it on your phone (do this while online)
- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**. Open it once from the new icon.
- **Android:** open the link in Chrome, tap the menu, then **Add to Home screen** or **Install app**.

Test it: turn on Airplane Mode and open the app from its icon.

## Notes
- Everything you type is saved on your phone only. Nothing is sent anywhere.
- On iPhone, the home-screen app keeps its own notes, separate from Safari. Use the icon at the event.
- If you change `index.html`, also change `VERSION` in `service-worker.js` so phones fetch the update.
