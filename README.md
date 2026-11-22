# Varshith A S — Portfolio

A single-file, dependency-free portfolio site.

## Files
- `index.html` — the entire site (HTML + CSS + JS + inline SVG artwork). **This is the only file you need.**
- `uploads/` — your original resume PDF and the reference screenshots. The resume is linked from the "View resume" button.

## Run it
Double-click `index.html`, or drag it into any browser. No build step, no server, no installs.

## What's inside
- **Wordmark** — "VARSHITH A S" drawn as an inline SVG dot-matrix (Nothing-style), with a dot pop-in animation that replays on hover.
- **Hero** — animated laptop with a live typing terminal.
- **Projects** — two cards, both clickable with a tabbed detail modal:
  - Traffic signal simulation: live light cycle (EW → NS) and cars that stop/go on the light.
  - Twitter Clone: 2018 bird that flaps and hovers in place.
- **Headings** — letter pop-in on scroll, plus a hover wave that scales, bolds and turns the letters lime.
- **Sections** — Projects, About, Experience, Education, Skills, Contact.
- Responsive down to small phones; honours `prefers-reduced-motion`.

## Editing tips
- Content lives in plain HTML — search for the visible text.
- Colours are CSS variables at the top of `<style>` (`--bg`, `--lime`, `--ink`, `--muted`).
- Project modal text lives in the `DATA` object inside the final `<script>` block.
- Traffic timing: the `PLAN` array (`ewGreen`, `ewAmber`, `nsGreen`, `nsAmber` with millisecond durations).
