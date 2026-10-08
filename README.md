# 4 A Better Tomorrow website

The redesigned website for 4 A Better Tomorrow (4abt.net), a Utah 501(c)(3) serving children in Independencia, Dominican Republic.

## How it works

- The whole site is one file: `index.html`. The photos and logo sit next to it.
- It is hosted free on GitHub Pages. There is no monthly fee.
- English and Spanish live side by side. Every piece of text has its English version in the page and its Spanish version in a `data-es="..."` attribute right next to it.

## Making a simple change

1. Open `index.html` on GitHub and click the pencil icon.
2. Find the words you want to change (Ctrl+F). Change the English text and the matching `data-es` Spanish text.
3. Click **Commit changes**. The live site updates in about a minute.

## Swapping a photo

Upload a new photo with the same file name (for example `hero.jpg`) using **Add file > Upload files**. Keep photos under about 1,500 pixels wide so the site stays fast.

## Updating the amount raised

Search `index.html` for `2,570` and replace it with the current Givebutter total.

## Pointing 4abt.net at this site

1. In this repository, go to **Settings > Pages > Custom domain**, enter `4abt.net`, and save.
2. At the domain registrar (GoDaddy), set DNS records for 4abt.net:
   - Four `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - A `CNAME` record for `www` pointing to `<github-username>.github.io`
3. Back in Settings > Pages, check **Enforce HTTPS** once it becomes available.
4. Cancel the GoDaddy Website Builder plan. Keep the domain registration itself.

## Taking ownership

This repository can be transferred to 4ABT's own GitHub account under **Settings > General > Transfer ownership**. Everything moves with it.
