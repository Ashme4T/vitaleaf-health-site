# VitaLeaf Health — website

Multi-page static site for the VitaLeaf Health SDG 3 group project (WAC, submitted to Dr. Lubna Rashid Malik).

## Files
- `index.html` — Home
- `about.html` — What We Do
- `impact.html` — Our Impact
- `roadmap.html` — Roadmap 2027–2029
- `communication.html` — Communication Strategy
- `contact.html` — Contact
- `style.css` — all styling (shared by every page)

No build step, no dependencies, no subfolders. Every file sits flat in this one folder, which avoids the broken-path problem you'd get from a nested `assets/` folder.

## Hosting on GitHub Pages
1. Upload **all seven files** (six `.html` files + `style.css` + this README) straight into the repo root, don't put them inside another folder.
2. Settings then Pages then Source: "Deploy from a branch" then Branch: `main`, folder `/ (root)` then Save.
3. Your site is live at `https://<username>.github.io/<repo-name>/`.

## Photo credits
Photos are hotlinked from Unsplash and Pexels (both free-to-use, no attribution legally required, but credited here anyway):
- Home hero: photo by Vitaly Gariev on Unsplash
- Impact page: photo by CDC on Unsplash
- Roadmap page: photo by Akil Mazumder on Pexels
- Communication page: photo by RDNE Stock project on Pexels
- Contact page: photo by James Lee on Pexels

## Editing
- Each page is its own HTML file, edit the one you want to change.
- Colors, fonts, spacing all live in `style.css` under `:root` at the top.
- The navigation menu is repeated at the top of every HTML file, if you rename a page or add a new one, update the `<nav class="site-nav">` block in all six files.
