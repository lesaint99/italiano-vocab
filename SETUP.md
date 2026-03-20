# 🇮🇹 Il Mio Vocabolario — Setup Guide

Your personal Italian vocabulary trainer, installable on your phone for free.

---

## Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it: `italiano-vocab`
4. Make sure it's set to **Public**
5. Click **Create repository**

---

## Step 2: Upload the App Files

In your new repository, click **Add file → Upload files** and upload ALL of these files:
- `index.html`
- `sw.js`
- `manifest.json`
- `icon-192.png`
- `icon-512.png`

Click **Commit changes**.

---

## Step 3: Enable GitHub Pages

1. Go to your repository → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under "Branch", select **main** and click **Save**
4. Wait ~60 seconds, then your app will be live at:
   `https://YOUR-USERNAME.github.io/italiano-vocab`

---

## Step 4: Install on Your Phone

### iPhone (Safari):
1. Open your app URL in Safari
2. Tap the **Share** button (box with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

### Android (Chrome):
1. Open your app URL in Chrome
2. Tap the **⋮** menu → **Add to Home screen**
3. Tap **Add**

The app will appear on your home screen like a native app! ✓

---

## Step 5: Connect Claude (Auto-add words)

Every time you ask me about an Italian word, I'll give you a code snippet to paste in the browser console to add that word automatically. For example:

```javascript
addWord('ossia', 'or else / or rather', 'A musical term for an alternative passage');
```

Just open your app, open the browser console (or DevTools), and paste it in.

---

## Features

- ✦ **5-word daily quizzes** — English → Italian
- ✦ **Spaced repetition** — words you miss come back sooner
- ✦ **Mastery tracking** — 5-star progress per word
- ✦ **Daily streak** — stay motivated
- ✦ **Works offline** — installed as a PWA
- ✦ **"ossia" already loaded** as your first word!

---

## Adding Words Manually

Tap the **Words** tab in the app and use the input fields at the top to add Italian/English pairs directly.
