# Nguyễn Tùng Dương — Portfolio

Personal portfolio site: **https://tugduong57.github.io/My-Portfolio/**

Plain HTML, CSS and a few lines of JavaScript — no build step, no third-party scripts,
no tracking. Light and dark themes follow the system setting, with a manual toggle.

## Structure

```text
index.html            single-page portfolio (featured work, experience, projects, skills, education, contact)
404.html              GitHub Pages "not found" page
projects/, experience/  redirects kept so old links still work
assets/css/style.css  all styles (colour tokens at the top)
assets/js/main.js     mobile menu, theme toggle, footer year
assets/img/           avatar, favicon, project images
```

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Before publishing changes

This repository is public. Do not commit API keys, tokens, server addresses, client data,
screenshots that show real employee data, or anything copied from private repositories.
