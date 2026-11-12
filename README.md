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

### 1. Your photo or logo
1. Copy your picture into the `images` folder (for example `images/amit.jpg`).
2. In `index.html` change `images/profile-placeholder.svg` to `images/amit.jpg`.
3. In `en/index.html` change `../images/profile-placeholder.svg` to `../images/amit.jpg`.

Tip: a square picture works best (it is shown as a circle).

### 2. Your WhatsApp number
In **both** pages, change `972XXXXXXXXX` to your number:
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
The "About me" text is a draft — edit it in both pages (look for **EDIT**).

## See it on your computer
Double-click `index.html` to open it in your browser.
