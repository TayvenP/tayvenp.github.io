# How to Create and Upload Favicons for Your GitHub Pages Site

A **favicon** (short for *favorite icon*) is the small image that appears in your browser tab, bookmarks, and mobile shortcuts.  
Adding a custom favicon is a simple way to make your site look professional and instantly recognisable.

This guide shows you how to **create** and **upload** favicons for a Jekyll site using the Chirpy theme.

---

## 1. Prepare Your Base Image
- First I started with my logo, a **square image**. You can use PNG, JPG, or SVG at least **512×512 px**.
- Keep it simple! Favicons are tiny, so bold shapes and high contrast work best.

---

## 2. Generate the Favicon Files
I found that this website generated my Favicon files in all the required sizes and formats in just a few minutes! [Real Favicon Generator](https://realfavicongenerator.net/).

1. Upload your base image.
2. Keep the default settings for compatibility.
3. Click **Generate your Favicons and HTML code**.
4. Download the generated package.

---

## 3. Clean Up the Package
From the downloaded files, **delete**:

- `browserconfig.xml`
- `site.webmanifest`

I only kept the `.png` and `.ico` files. Chirpy doesn’t need the extra config files.

---

## 4. Add Favicons to Your Project
1. I then created the directory: `assets/img/favicons/`
*(Create this folder if it doesn’t exist.)*
2. I uploaded the generated `.png` and `.ico` files to the /favicons directory.
3. I selected Commit Changes. Comment noted - Uploading Favicon.

---

## 5. Wait for the Changes to Appear
It took a while to sync to the webpage, but it automatically changed after some time, so be patient. 

---
