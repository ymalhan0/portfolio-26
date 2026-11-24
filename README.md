# Yukti Malhan · Portfolio

Plain HTML/CSS site. No build step: open `index.html` in a browser to preview.

## Pages
- `index.html` – home (binder-paper intro + project cards)
- `compliance.html` – Utility Regulatory Compliance, part 1
- `compliance-2.html` – Utility Regulatory Compliance, part 2 (agentic work)

Billing, Support and Bundling cards (and "About me") link to the current site at
https://ymalhan0.github.io/portfolio-23/ until those pages are rebuilt here.

## Assets
- `assets/img` – images (webp/jpg/png)
- `assets/video` – Compliance hero videos
- `assets/YM_Resume.pdf` – resume linked from "View my resume"

## Notes
- The Compliance pages include `<meta name="robots" content="noindex">` so search engines skip them.
- Fonts load from Google Fonts (Bricolage Grotesque, Inter, Caveat).

## Publish on GitHub Pages
1. Create a new repo on GitHub (e.g. `portfolio`), then push this folder:
   ```
   git init
   git add .
   git commit -m "New portfolio"
   git branch -M main
   git remote add origin https://github.com/ymalhan0/<repo-name>.git
   git push -u origin main
   ```
2. In the repo: Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. The site appears at `https://ymalhan0.github.io/<repo-name>/` within a minute or two.
