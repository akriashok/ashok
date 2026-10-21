# Akiri Ashok Kumar — Portfolio

Personal portfolio site: a single static page (`site/index.html`) with light and dark themes and no build step.

**Live:** https://akriashok.github.io/ashok/

## Deploy

`.github/workflows/pages.yml` publishes the `site/` folder to GitHub Pages on every push to `main`
(and to the `claude/exciting-fermat-jsfo8w` branch) or when run manually from the Actions tab.

One-time setup: in the repo go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.

## Edit

Open `site/index.html` and change the text in the Experience, Projects, Skills, Credentials and Contact sections.
To preview locally: `python3 -m http.server -d site 8000` and open http://localhost:8000.
