# Yesteryear Icons 🎬

A private, password-protected glamour gallery — nostalgic icons from a bygone era.

Live at: **https://jmcpublic.github.io/yesteryear-icons/**

---

## Getting it live (one time only)

1. Go to [github.com/new](https://github.com/new) and create a repo called `yesteryear-icons` — set it to **Public**
2. Upload `index.html` and the `images/` folder
3. Go to **Settings → Pages**, set source to `main` branch, root folder — click Save
4. Wait about a minute. Done.

---

## Adding photos

1. Open your repo on GitHub and click into the `images/` folder
2. Click **Add file → Upload files** (or drag photos straight onto the page)
3. **Name the file the person's name** — e.g. `Jessica Biel.jpg` or `Rhona Mitra.png`
4. Commit — the gallery updates automatically

A short biography is pulled from Wikipedia based on the filename. If the filename is a camera dump (like `IMG_4521.jpg`), the card shows as **Seymore 1**, **Seymore 2**, etc.

Supported formats: JPG, PNG, WebP, GIF, AVIF

---

## Passcode

Default: **1950**

To change it, open `index.html` in a text editor and find this line near the bottom:

```
const PASSCODE = "1950";
```

Change `1950` to whatever you like, save, and re-upload to GitHub.

---

*For personal nostalgia only. All images © their respective rights holders.*
