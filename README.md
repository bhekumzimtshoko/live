# Bhekumzi Mtshoko — Personal Site (Redesign)

Static one-page site for Bhekumzi Mtshoko, Entrepreneur, Founder & CEO of Mtshoko Security Services and Mtshoko Security Training College.

Same content and images as the current site, new layout:

- Split hero (copy left, portrait right) with an overlapping stats strip
- Editorial profile with sticky portrait and pull quote
- Brass statement band
- Ventures as timeline rows (2013 / 2019) beside a sticky photo
- Bento gallery with keyboard-accessible lightbox
- Connect section with contact list and social links

## Structure

```
index.html
css/styles.css
js/main.js
images/        # unchanged from the original site
robots.txt
sitemap.xml
```

No build step. Open `index.html` directly or serve the folder (e.g. `http://localhost/2026/bklivenew/` under WAMP).

## Publish to GitHub Pages

```bash
git init
git add .
git commit -m "Redesign: new layout, same content and images"
git branch -M main
git remote add origin https://github.com/<user>/<repo>.git
git push -u origin main
```

Then enable Pages under **Settings → Pages → Deploy from branch → main / root**.
