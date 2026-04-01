# Liberty USVI Site Survey — PWA Deployment Guide

## Files in this package
```
index.html      ← Main survey app
manifest.json   ← PWA manifest (makes it installable)
sw.js           ← Service worker (enables offline use)
icon-192.png    ← App icon (home screen, small)
icon-512.png    ← App icon (splash screen, large)
```

---

## Option A — Deploy FREE on Netlify (Recommended, 5 minutes)

1. Go to https://netlify.com and create a free account
2. From your dashboard click **"Add new site" → "Deploy manually"**
3. Drag and drop this entire folder onto the page
4. Netlify gives you a URL like: `https://liberty-usvi-survey.netlify.app`
5. Share that URL with your subcontractors

**Custom domain** (optional): In Netlify settings you can point your own domain
e.g. `survey.yourcompany.com` — free SSL included.

---

## Option B — Deploy FREE on GitHub Pages

1. Create a free account at https://github.com
2. New repository → name it `liberty-usvi-survey` → set to **Public**
3. Upload all files in this folder
4. Go to Settings → Pages → Source: **main branch / root**
5. URL will be: `https://yourusername.github.io/liberty-usvi-survey`

---

## How subcontractors install the app

### iPhone / iPad (iOS)
1. Open the URL in **Safari** (must be Safari for iOS install)
2. Tap the **Share button ↑** at the bottom
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"** — app icon appears on home screen
5. Open from home screen — runs full screen like a native app

### Android
1. Open the URL in **Chrome**
2. A banner will automatically appear: **"Add Liberty Survey to Home Screen"**
3. Tap **Install** — done
4. Or: tap Chrome **⋮ menu → "Add to Home Screen"**

---

## Offline Use
Once installed, the app works with **no internet connection**.
Subcontractors can fill out the entire survey on a tower with zero signal.
PDF export also works fully offline.

---

## Updating the App
When you make changes to index.html, just re-upload to Netlify.
The service worker will automatically update on all devices within 24 hours,
or immediately when the user closes and reopens the app.

---

## Support
For deployment help contact your project manager.
