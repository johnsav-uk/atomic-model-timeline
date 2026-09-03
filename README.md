# Development of the Model of the Atom

An interactive revision and teaching tool for **AQA GCSE Chemistry (8462), topic 4.1.1.3 — Higher Tier**.

**▶ [Open the tool](https://johnsav-uk.github.io/atomic-model-timeline/)**

A timeline of six models — Democritus, Dalton, Thomson, Rutherford, Bohr and Chadwick — each with a
rotatable 3D model, an exam-style 2D diagram, and revision notes written against the AQA
specification wording and mark schemes.

## What's in it

- **3D models** you can rotate and zoom, with protons marked **+** and electrons marked **−**.
  Every model shows the same neutral carbon atom, so what changes between nodes is the *model*,
  not the atom.
- **2D exam diagrams** — the flat, labelled representation students actually have to draw, with
  electrons placed by the usual GCSE convention and a "how to get the marks" note on each one.
- **The alpha scattering experiment** — a live simulation of Geiger and Marsden's experiment:
  a collimated alpha beam, a gold foil, and a 360° zinc sulfide screen that flashes where each
  particle lands, with a running tally of how many pass straight through, deflect, or bounce back.
  A **plum pudding prediction** toggle shows what the old model predicted, for contrast.
- **Revision notes** for each scientist: key concept, crucial experiment, why the previous model
  was replaced, AQA keywords, and a Higher Tier exam tip with mark-scheme wording.
- **Presentation mode** — press `P` for full-screen, projector-sized text that builds one point at
  a time for teaching to a class.

## Keyboard

| Key | Action |
| --- | --- |
| `←` `→` | Move through the timeline |
| `2` | Toggle the 2D exam diagram |
| `P` | Presentation mode |
| `Space` / `→` | Next point (in presentation mode) |
| `Esc` | Back to the 3D model / exit presentation |

## Technical

A single self-contained HTML file. Three.js and Roboto are loaded from a CDN, so the page needs an
internet connection the first time it runs; if the 3D engine cannot load, the revision notes still
work and the page says so rather than showing a blank screen.
