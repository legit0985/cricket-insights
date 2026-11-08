# Telegram Landing Page

Ads ke liye simple landing page jo users ko Telegram channel par bhejta hai.

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
