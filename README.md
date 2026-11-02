# Kitab website

Static site for GitHub Pages. Files:

- `index.html` — landing page (search-optimised, links to the App Store)
- `privacy.html` — privacy policy (the URL App Store Connect and Play Console ask for)
- `config.json` — app update control file (`minVersion` forces an update; `latestVersion` shows the banner)

## Publish on GitHub Pages

1. Create a new public repository on github.com named `kitab`.
2. Upload these four files to it (Add file → Upload files).
3. Settings → Pages → Build and deployment → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is live at:
   - https://abdulrafey38.github.io/kitab/
   - https://abdulrafey38.github.io/kitab/privacy.html
   - https://abdulrafey38.github.io/kitab/config.json
