# ralf1q — personal website

A clean, dark one-page site with subtle animations for **ralf1q**: social media marketing specialist and founder of
**FrameDuoVisuals** ([Instagram](https://www.instagram.com/frameduovisuals/)), a social media marketing agency launching soon.

Plain HTML and CSS, with no build step. Everything is in `index.html`.

Live URL (once GitHub Pages is on): https://ralf1qdev.github.io/ralf1qdeva/

## Files
- `index.html`: the page, with SEO tags and structured data (Person + FrameDuoVisuals organization)
- `robots.txt`, `sitemap.xml`: for search engines
- `llms.txt`: a short plain-text profile for AI assistants
- `404.html`: the "page not found" page
- `assets/`: favicon, app icon and social preview image

## Go live
1. In this repo, go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, pick this branch and `/ (root)`, then save.
2. After a minute, open https://ralf1qdev.github.io/ralf1qdeva/.

## Using a custom domain later
Replace `https://ralf1qdev.github.io/ralf1qdeva/` with the new address in `index.html`, `robots.txt`,
`sitemap.xml` and `llms.txt`, change `/ralf1qdeva/` to `/` in `404.html`, and add a `CNAME` file containing the domain.
