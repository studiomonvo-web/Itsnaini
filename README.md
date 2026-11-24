# Itsnaini Nurfaizah, portfolio site

Open `index.html` in a browser. No build step. Internet is only needed for the Google Fonts (Newsreader and Figtree).

## Fill in before you share the link
Open `index.html`, search for `const PROFILE` near the bottom, and fill in `email` and `linkedin`.
The contact buttons appear automatically once they are filled in.

## Privacy
All 15 session images show participants' real faces and names, as requested. Keep the deployed link private
until you have permission, or replace the images in `assets/img/` with blurred versions before sharing it.

## Please confirm these facts
- Name spelling: "Itsnaini Nurfaizah"
- Training Coordinator at B/NDL Studios, since 2023
- The before / during / after text describes how you work in general terms, built from the responsibilities you listed. Edit it to match your real routine.
- The Medium essay is described only from its title.
- The log is described as the record you work from. Adjust the wording if you only coordinated part of it.

## Folders
- `assets/img/` the 15 session images and the hero crop (webp)
- `index.html` the whole site (CSS, JS and the 85-entry training log are inside)

## Case studies (new)
Open `index.html` and search for `CASE_STUDIES`. Each case study is one independent entry; add, reorder, replace or delete entries there and the layout follows. Items can be text, links `{text, href}` or placeholders `{placeholder: "..."}`. The "Your next case study" entry is a template.
Set `SHOW_PLACEHOLDERS = false` before you share the link: every placeholder and the template entry then disappear.
Everything in the entries comes from the existing log, sessions, writing and time-zone sections. Please check each "My involvement" line: it states the general responsibilities already on this site, and you should add what you personally did on each programme.

## Animation (new)
- Reveals, bloom and parallax are plain CSS plus a small IntersectionObserver. Nothing is added when "reduce motion" is on.
- Botanical artwork is in `assets/flora/` (soft-focus branches, generated artwork). Swap in your own cherry blossom photography with the same file names and transparent backgrounds.

## Deploy on Netlify
Drag the folder (or the zip) onto app.netlify.com/drop. `_headers` sets a one-day cache for images.
