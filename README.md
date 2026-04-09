# Weight Tracker

A personal daily weight tracker PWA. Works offline. Installable on iPhone and Android.

## Files

```
index.html      — the app
manifest.json   — PWA config (name, icons, colors)
sw.js           — service worker (offline support)
icon.svg        — app icon source (export to icon-192.png and icon-512.png)
icon-192.png    — app icon (generate from icon.svg)
icon-512.png    — app icon (generate from icon.svg)
```

## Deploy to GitHub Pages

1. Create a new GitHub repository (can be private or public)
2. Upload all files to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch, **/ (root)** folder → click **Save**
6. Your app will be live at `https://yourusername.github.io/your-repo-name/`

> It may take 1–2 minutes for GitHub to build and publish the first time.

## Install on iPhone

1. Open the app URL in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — it appears on your home screen like a native app

## Notes

- All data is stored locally on your device (localStorage)
- No account or server required
- Works fully offline after first load
- Export icon.svg at 192×192 and 512×512 px to generate the PNG icons
