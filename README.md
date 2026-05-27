# Forge

**Team Forge — Canva ImpactHack**

---

## What is this?

Forge is a career path explorer for students who don't fit a single linear track. You answer a short reflective quiz — one word for your legacy, your field, your role, what else excites you — and it surfaces three possible degree journeys as interactive branching trees.

**This repo is a single HTML file demo.** It was designed, built, and pitched in a hackathon sprint. There's no backend, no API, no framework — just one self-contained `forest.html` file with vanilla JS, SVG trees, and hardcoded path data.

---

## The idea

Most career tools show you a ladder. Real paths branch, merge, loop back, and cross over.

Medicine students especially feel this — you might be on track for surgery *and* building a startup *and* questioning the whole thing by second year. Forge makes that visible: not a list of electives, but a **map of where your choices could take you**, with notes from students who've stood at the same crossroads.

The Canva angle: your forge is something you'd want to **save, share, and grow over time** — a living visual artifact of who you're becoming, not a one-off quiz result.

---

## What's in the demo

- **Legacy prompt** — one word for what you want to leave behind (no name required)
- **Conversation flow** — field, role, specialisation, multi-select interests, and how you want to be remembered
- **Generation screen** — animated "forging" sequence while paths load
- **Three career trees** — scrollable SVG path maps:
  - *Neurosurgeon-Founder*
  - *Medical Innovator*
  - *The Unexpected Path*
- **Shared nodes** — tap glowing nodes (MMES, Monash Generator, MGC2230) to see a wall of sticky-note testimonials from other students who walked that step
- **Save path** — fake export toast (PNG/PDF) to signal the Canva save flow
- **Mobile layout** — full-screen tree view with vertical scroll on phone

---

## Running it

No install, no build step.

```
forest.html
```

Open `forest.html` in a browser. That's it.

**GitHub Pages:** enable Pages from the `main` branch (root folder). Optionally copy to `index.html` so the site loads at the repo URL without a filename.

**On mobile:** host it (GitHub Pages, Netlify, or `npx serve .`) and open the link on your phone — don't rely on `file://`.

---

## What it isn't

This is a **prototype made for a pitch**, not a production app. It has:

- Hardcoded trees and student notes (Monash medicine–focused demo data)
- No real path generation — the quiz captures answers but all three trees show regardless
- No authentication, persistence, or Canva API integration
- A fake save/export flow (toast only)

The point was to demonstrate the concept and UX convincingly in the time available.

---

## Repo contents

| File | What it is |
|------|------------|
| `forest.html` | The full Forge demo |
| `Pitch_Deck.pdf` | Hackathon pitch deck |

---

## Built by

Made for the Canva ImpactHack — sprint build, one HTML file, team name **Forge**.

Didn't make the final round. Still think the idea's worth finishing.
