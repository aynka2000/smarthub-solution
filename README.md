# Smart Hub Solution — website

Static company website for Smart Hub Solution (smarthubsolution.com)

## How it is published

- Hosting: Netlify (free Starter), site `transcendent-bombolone-46aa1b`,
  custom domain `smarthubsolution.com`.
- This repo is the source of truth. Pushing to `main` deploys automatically
  (Netlify is linked to this repo; no build command, publish directory is
  the repo root).

## How to edit

- Text: edit the page's `index.html` — `index.html` is the homepage,
  `about-us/index.html` is About Us, `contact-us/index.html` is Contact Us,
  and so on. Change only the visible words, save, commit, push.
- Photos: replace a file in `assets/theme/` or `assets/uploads/` with a new
  file of the same name, or update the `src` in the page.
- Images are plain files; there is no build step and no editor to install.
  Edits can be made right on github.com.

## Structure

- `index.html` — homepage
- `<page>/index.html` — one folder per page (23 pages)
- `assets/style.css` — site stylesheet
- `assets/theme/`, `assets/uploads/` — images
- `assets/pdf/` — white paper PDF

## Do not change

- File and folder names (URLs depend on them).
- The domain's DNS records — they point the domain at this site and carry
  the email setup. If DNS ever needs work, ask Siva first.
