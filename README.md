# Amit Sisso – Event Photography

Portfolio website for Amit Sisso, event photographer in Ashdod.

Live site: https://amitsisso1-ctrl.github.io

## Files

| File | What it is |
|------|-----------|
| `index.html` | Hebrew page (opens first) |
| `en/index.html` | English page |
| `style.css` | The design (colors, fonts, sizes) for both pages |
| `images/` | All pictures |

## How to update the site

Every place you need to change is marked in the HTML with the word **REPLACE**.
Search for it (Ctrl+F) in both `index.html` and `en/index.html`.

### 1. Logo
The logo at the top is `images/logo.png` (a trimmed copy of `my logo.png`).
To change it, replace `images/logo.png` with a new file of the same name.
The site colors (black & white) match the logo — they are at the top of `style.css`.

### 2. Your WhatsApp number
Already set to `https://wa.me/972547833704`. To change it, edit the WhatsApp link in **both** pages:
start with `972`, then your number **without the first 0**.
Example: `050-1234567` → `https://wa.me/972501234567`

### 3. Gallery photos (the slider)
1. Create the folder `images/gallery/` and put your photos there
   (for example `photo-01.jpg` … `photo-10.jpg`).
2. In `index.html` change each `images/photo-placeholder.svg` to `images/gallery/photo-01.jpg`, etc.
3. In `en/index.html` do the same, but with `../` at the start: `../images/gallery/photo-01.jpg`.

Tip: make photos smaller before uploading (about 1600px wide, under 500 KB each) so the site loads fast on phones.
Portrait photos (tall, 4:5) look best in the slider.

### 4. Text
Under your name there is a quote by David Alan Harvey. To change it, edit the `<blockquote>` in both pages.

## See it on your computer
Double-click `index.html` to open it in your browser.
