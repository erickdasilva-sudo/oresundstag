# Øresundståg Tracker

Live departure board for Øresundståg between **Malmö Hyllie** and **Copenhagen Airport (CPH T3)** — in both directions.

## Features
- Live departures with real-time delay info (red = delayed, strikethrough = cancelled)
- "Can I catch it?" slider — shows if you can make the next train
- Border control reminder for CPH → Hyllie direction
- Works as a home screen app on iPhone and Android
- API key saved locally — type it once, never again

---

## Setup on GitHub Pages (5 minutes)

### Step 1 — Create a new repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `oresundstag` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload the files
1. In your new repo, click **Add file → Upload files**
2. Upload both files: `index.html` and `manifest.json`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch, **/ (root)** folder
4. Click **Save**
5. Wait ~60 seconds, then your app is live at:
   `https://YOUR-USERNAME.github.io/oresundstag/`

### Step 4 — Get your free API key
1. Go to [labs.rejseplanen.dk](https://labs.rejseplanen.dk)
2. Click **Opret konto** (create account) — completely free
3. Log in and find your **accessId**
4. Open your app, paste the key, hit **Save** — stored on your device

### Step 5 — Add to your phone home screen

**iPhone (Safari):**
1. Open your GitHub Pages URL in Safari
2. Tap the Share button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — done

**Android (Chrome):**
1. Open your GitHub Pages URL in Chrome
2. Tap the three dots menu
3. Tap **Add to Home screen**
4. Tap **Add** — done

The app opens full screen with no browser bar, like a native app.

---

## Station IDs (Rejseplanen)
- Malmö Hyllie: `8600626`
- Copenhagen Airport T3: `8600645`
- Kastrup: `8600644`
- Malmö C: `7400003`

## Notes
- App refreshes every 30 seconds automatically
- Demo mode runs without an API key (simulated times)
- The 5-6 min border stop at Hyllie (Sweden-bound) is scheduled, not a delay
