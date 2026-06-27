# Curio Media - legal pages (privacy + terms)

Static pages that give TikTok / Meta a **public privacy-policy + terms URL** for the developer app
review. Host free on GitHub Pages.

## Files
- `index.html` - landing, links to both
- `privacy.html` - Privacy Policy (the URL TikTok/Meta require)
- `terms.html` - Terms of Service

## Host on GitHub Pages (free, ~3 min)
1. Create a new GitHub repo named `curio-media-legal` (public).
2. Push this folder:
   ```
   git init
   git add .
   git commit -m "Curio Media legal pages"
   git branch -M main
   git remote add origin https://github.com/<your-username>/curio-media-legal.git
   git push -u origin main
   ```
3. Repo -> Settings -> Pages -> Source = `Deploy from a branch` -> Branch = `main` / `/ (root)` -> Save.
4. After ~1 min your URLs are live:
   - Privacy: `https://<your-username>.github.io/curio-media-legal/privacy.html`
   - Terms:   `https://<your-username>.github.io/curio-media-legal/terms.html`

Use those two URLs in the TikTok dev-app form and the Meta app settings.

> Tip: a custom domain (e.g. `curio.media`) can be added later under Pages -> Custom domain; the
> github.io URLs are perfectly acceptable for the app review.
