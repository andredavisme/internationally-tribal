# Internationally Tribal

> A bold geometric brand logo that morphs into a face — built as an example of AI-assisted creative development.

![Black, white, and red geometric logo with pirate-flag inspired I and T letterforms](https://andredavisme.github.io/internationally-tribal/)

---

## 🔴 Live Pages

| Page | URL |
|------|-----|
| Logo Animation | [andredavisme.github.io/internationally-tribal/](https://andredavisme.github.io/internationally-tribal/) |
| Student Activity Guide | [andredavisme.github.io/internationally-tribal/activity.html](https://andredavisme.github.io/internationally-tribal/activity.html) |

---

## What It Does

- Loads a bold black/white/red SVG logo inspired by pirate-flag aesthetics
- 2 seconds after page load, the logo's geometric shapes morph into a sharp tribal face
- The face holds, then fully reverses back to the original logo
- No UI, no buttons — pure visual storytelling
- Built entirely with HTML, inline SVG, and [Anime.js](https://animejs.com/)

---

## Tech Stack

- **HTML + Inline SVG** — all shapes are vector polygons, no images
- **Anime.js 3.2** — handles SVG polygon point morphing via `anime.timeline()`
- **GitHub Pages** — zero-cost static hosting straight from this repo

---

## 🎓 Student Activity: AI as a Creative Tool

**→ [Open the Activity Guide](https://andredavisme.github.io/internationally-tribal/activity.html)**

This project was built as a demonstration for a hands-on student activity about using AI as a *creative collaborator* — not a replacement for human creativity.

### What the activity covers:

- Why the fear of AI is real — and where it actually comes from
- How the "wrong" way to use AI (outsourcing your thinking) is different from the right way
- A 5-phase guided build: design a logo → iterate with AI → add animation → tune the face → publish
- Reflection questions that surface what AI *can't* do for you
- "Go Further" extensions: add sound, interactivity, apply to any brand

### Core message:

> **AI is a hammer. A person with a hammer builds the house.**
> Every creative decision in this project — the brand name, the aesthetic, the colors, the pirate-flag concept, the face transformation — came from a human. AI handled the code syntax. The vision was always human-led.

---

## How to Remix This

1. Fork this repo
2. Open `index.html` and update the SVG polygon `points` to match your brand's letterforms
3. Adjust the morph target coordinates in the Anime.js timeline to match your face design
4. Update colors in the SVG `fill` attributes
5. Enable GitHub Pages on your fork — done

---

## License

MIT — free to use, remix, and build on.
