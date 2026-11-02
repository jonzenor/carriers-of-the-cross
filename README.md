# Carriers of the Cross

Portable, static guild website. No database, accounts, or build dependencies.

## Preview

Run `python3 -m http.server 8080 --directory dist` and open http://localhost:8080.

## Deploy anywhere

Publish the contents of `dist/` to any static host, including GitHub Pages, Cloudflare Pages, or Netlify. Keep root-relative paths when hosting at a domain root. For GitHub Pages use a custom domain or adjust root-relative links for a repository subpath.

## Content

The HTML in `dist/` is the deployment source and can be edited directly. Run `python3 build.py` to regenerate the site from the page templates, `content/`, and charter text. Python’s standard library is sufficient. `charter.txt` preserves the public charter content.

Sources: cotc.guildtag.com public wiki, and the Carriers of the Cross Google Drive charter updated October 30, 2026. The newer Drive charter was used for the expanded mission and rank structure; the wiki uses an older rank structure. Officer agenda items are excluded.

Artwork: reference guild poster in `dist/assets/guild-banner.png` and generated cinematic hero in `dist/assets/hero-epic.webp`. Custom fantasy theme in `dist/epic.css`. Typography: Cinzel and Inter from Google Fonts, with local system fallbacks.

Discord invitation: https://discord.gg/Q3vse3prFg
