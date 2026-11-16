# Landscape Climate Resilience (team draft)

A one-page website that summarises climate hazards, adaptation actions, techniques, what works and future measures, country by country, for the KAZA, SOKNOT, Congo Basin and other landscapes. Every answer has page references, a confidence level and an [Official]/[Other] source tag.

The site reads its content from `data.json`, `map.json` and `ndgain.json`; `index.html` holds the layout and code.

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `landscape-climate-resilience`).
2. Upload everything in this folder, including the hidden `.nojekyll` file, to the top level of the repository (Add file → Upload files, or `git push`).
3. In the repository go to **Settings → Pages**. Under "Build and deployment" choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/landscape-climate-resilience/`.

## Updating it

Replace `data.json` (and `index.html` if the layout changed) with the new versions and commit. Nothing needs building on GitHub.

## Notes

- Opening `index.html` by double-clicking will show "The analysis data did not load", because browsers block reading local files. View it through GitHub Pages, or locally with `python3 -m http.server` in this folder and then http://localhost:8000.
- On a free GitHub account, Pages sites are public, even from a private repository.
- The only outside resource is the Open Sans font from Google Fonts.
