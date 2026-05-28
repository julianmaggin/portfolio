# Julian Maggin — Portfolio

Editorial-style portfolio scaffold. Single `index.html` + `images/` folder.

## How to view it now

Double-click `index.html` to open in your browser. It works as a standalone webpage. To export as PDF for sending: open in Chrome → Print → Save as PDF → set background graphics ON.

## To fill in B&D Doors (Project 04)

Look in `index.html` for the comment `<!-- ═══ 04 — B&D DOORS ═══`. You'll find:

1. **Hero image placeholder** — replace `<div class="placeholder">…</div>` inside the `<figure class="hero-image">` with `<img src="images/bd-hero.png" alt="..." />`. Drop the actual image file into `images/`.
2. **Three supporting image placeholders** in the photos grid below the body copy. Same pattern.
3. **Narrative copy** — there's a `[Specific install metrics to be added here.]` placeholder mid-paragraph. Drop in real numbers if you have them (e.g. "reducing installation from X steps to Y" or "cutting install time by Z minutes").

What to send me if you want me to do the swap: 2–4 images, plus the specifics on what the consolidated product actually was, which legacy SKUs it replaced, and the new market segment it unlocked.

## To hand this off to Claude Design

Claude Design accepts code/HTML as input. Upload `index.html` along with the `images/` folder. Useful prompts once it's loaded:

- "Refine the typography pairing — keep Fraunces but try a different sans for body."
- "Tighten the project page rhythm so each project feels distinct."
- "Add subtle motion to the project headers — staggered fade-in on scroll."
- "Improve the B&D Doors section — make it visually equal to the others once images are added."
- "Make the hero image on each project more cinematic."

The design system is already established (CSS variables at the top of `index.html`), so Claude Design can adjust within it rather than starting from scratch.

## Type system

- **Display** — Fraunces (variable serif, opsz + SOFT axes for editorial feel)
- **Body** — Bricolage Grotesque
- **Mono / metadata** — JetBrains Mono

## Color tokens

- `--paper` — `#ECE5D8` (warm cream background)
- `--paper-deep` — `#E2DAC8` (subtle contrast for index/closing band)
- `--ink` — `#1A1815` (warm black text)
- `--ink-soft` — `#4A4640` (secondary text)
- `--ink-muted` — `#8A8275` (tertiary / labels)
- `--accent` — `#8B3A1E` (burnt sienna — references the Caroma bronze finish)

## Things worth checking before sending

- **Years** on each project. I made reasonable guesses (Hai 2022, Fuse 2023, Contura 2023) — adjust to actuals.
- **Caroma Contura Good Design Award** — confirm wording. I have it as "Good Design Awards · Contura Collection" since the original portfolio described the *collection* as recognised, not the handset specifically.
- **Patent on Gethai Fuse** — confirm "patent pending" status is still accurate.
- **Volume / retail descriptors** in the Hai section.
