# Thoom’s Family Tree — V14 Cinematic Heritage

A static, view-only family tree website for GitHub Pages. Built with HTML, CSS, and vanilla JavaScript.

## Files
- `index.html` — page structure
- `style.css` — cinematic dark theme and responsive styles
- `script.js` — tree rendering and interaction logic
- `family-data.js` — supplied family records (preserved unchanged)
- `images/placeholder.svg` — placeholder asset, if used

## Publish on GitHub Pages
1. Back up the current repository or create a branch.
2. Replace `index.html`, `style.css`, and `script.js` with the V14 files.
3. Keep your existing `family-data.js` unchanged; the included copy is preserved from the supplied file.
4. Commit and push. Wait for GitHub Pages to deploy, then hard-refresh the site (Ctrl+F5).

## Notes
- The visual redesign keeps the existing JavaScript interaction engine rather than rewriting family relationships.
- Visitors can explore the tree but the static site has no visitor editing feature. Public GitHub repositories expose their source data.
- Google Fonts are loaded remotely; system fallbacks remain available if offline.
- Test search, branch filters, profile panels, relationship tracing, timeline, mini-map, and PDF printing on the deployed site before sharing.
