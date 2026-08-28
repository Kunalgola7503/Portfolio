# Kunal Gola — Portfolio Site

Static site, no build step. Ready for GitHub Pages.

## Deploy to GitHub Pages

1. Create a new repo (e.g. `kunal-portfolio`) or use an existing one.
2. Copy all files in this folder (`index.html`, `style.css`, `script.js`, `assets/`) into the repo root.
3. Add your resume PDF as `Kunal_Gola_Resume.pdf` in the repo root (the "Download CV" button links to this exact filename).
4. Commit and push to `main`.
5. In the repo: **Settings → Pages → Source → Deploy from branch → `main` / root**.
6. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

If you want it at `https://<your-username>.github.io/` directly (no repo name in the URL), name the repo exactly `<your-username>.github.io`.

## To-do before launch
- [x] Add `Kunal_Gola_Resume.pdf` to the root (Done!)
- [x] Swap in real project links on GitHub (Done!)
- [ ] Certification images: once you send them, they can replace the current text-only cert pills with actual badge graphics
- [ ] Double check phone/email are okay to have public before pushing

## Structure
```
index.html    — all content/sections
style.css     — design tokens + styles (edit --accent etc. at the top to retheme)
script.js     — mobile nav, accordion, scroll-reveal
assets/
  headshot.jpg
```
