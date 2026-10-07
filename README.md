# Corona x Braamfontein — Case Study Page

A single-page portfolio case study built for **Lucky Nhlanhla Mqadlana**, documenting the *Log Off. Lime In.* public art installation created for Corona's South African summer campaign in Braamfontein, Johannesburg.

---

## Project Overview

This page presents the full creative journey behind a 180° billboard and public mural installed at Braamfontein Square — from initial concept sketches through to final execution and impact. The design mirrors the aesthetic of the artwork itself: dark, textured, and typographically bold.

---

## Tech Stack

- **HTML5** — semantic markup, no frameworks
- **CSS3** — custom properties, CSS Grid, Flexbox, responsive media queries
- **Google Fonts** — [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) (display headings) + [Permanent Marker](https://fonts.google.com/specimen/Permanent+Marker) (hand-lettered accents)
- No JavaScript, no build tools — open directly in a browser

---

## File Structure

```
Corona_/
├── index.html          # Main page markup
├── styles.css          # All styles
├── README.md           # This file
└── assets/
    ├── CoronaLogo.png          # Corona brand logo
    ├── Afternoon.jpeg          # Hero / gallery image
    ├── CoronaMnaka.jpg         # Concept sketch image
    ├── Corona2.jpg             # Finished mural image
    ├── CoronaExtra.jpeg        # Gallery — night shot
    ├── LogOff.jpeg             # Gallery — evening shot
    ├── location-pin-svgrepo-com.svg
    ├── binoculars-4-svgrepo-com.svg
    └── calendar-small-svgrepo-com.svg
```

---

## Page Sections

| Section | ID | Description |
|---|---|---|
| Hero | — | Full-bleed night photo, campaign title, client meta |
| Project Overview | `#work` | Brief + concept sketch, tags |
| The Idea | — | Creative rationale + finished mural photo |
| Gallery | `#gallery` | Three-column photo grid |
| Execution & Impact | `#lab` | Stats (location, visibility, duration) |
| Footer | `#about` | Identity + contact link |

---

## Running Locally

No build step needed. Just open the file:

```bash
# Option 1 — double-click index.html in your file explorer

# Option 2 — serve with any static server, e.g. VS Code Live Server
# or:
npx serve .
```

The Google Fonts load from the CDN, so an internet connection is needed for the correct typography to render.

---

## Design Notes

- **Colour palette** — near-black background `#090909`, off-white `#f5f4ef`, accent yellow `#f3c800`
- **Display font** — Bebas Neue for the large condensed headings (LOG OFF. LIME IN., section titles)
- **Accent font** — Permanent Marker for hand-lettered callouts (BRAAMFONTEIN, THIS IS LIVING, captions)
- **Layout** — CSS Grid throughout; hero uses absolute positioning for the overlapping image panel
- **Images** — `width: 100%; height: auto` with no cropping so every photo displays in full

---

## Client

**Corona** (AB InBev South Africa)
Campaign: *This Is Living / Log Off. Lime In.*
Location: Braamfontein Square, Johannesburg
Installation period: 2024 — 2027

---

*Built by Kazadi Mukendi for: Lucky Nhlanhla Mqadlana — Artist / Creative Director / Visual Thinker*
