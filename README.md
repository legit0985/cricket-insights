# Telegram Landing Page

Ads ke liye simple landing page jo users ko Telegram channel par bhejta hai.

## Live links (ads mein yahi lagao)

- **Vercel:** https://cricket-insights.vercel.app
- **GitHub Pages (backup):** https://legit0985.github.io/cricket-insights/

Dono hamesha online rehte hain, kuch run karne ki zarurat nahi.

## Page badalne ke baad

- **GitHub Pages:** `git push` karte hi 1-2 minute mein apne aap update.
- **Vercel:** apne aap update nahi hota. Push ke baad yeh chalao:

```bash
vercel deploy --prod
```

## Localhost par chalao

```bash
python3 -m http.server 8080
```

Phir browser mein kholo: http://localhost:8080

## Kya badalna hai (sab `index.html` mein)

- **Telegram link**: `https://t.me/+lIiPpnnafpY4Yjdl` (2 jagah hai)
- **Naam**: `CRICKET INSIGHTS`
- **Logo**: `logo.jpg` folder mein daalo aur `index.html` mein comment wali line use karo
- **Meta Pixel**: upar `var PIXEL_ID = "";` mein apna Pixel ID daalo. Button click par `Lead` event jata hai.

## Live karna (GitHub Pages)

Repo → Settings → Pages → Branch: `main`, folder: `/ (root)` → Save.
Link milega: `https://<username>.github.io/<repo-name>/`
