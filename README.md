# The 11 Dimensions of M-Theory — Interactive Field Guide

An interactive, browser-based visualization that walks through all eleven dimensions of
M-theory one at a time — from a single point, up through the space and time we live in,
and out to the curled-up extra dimensions and the Calabi–Yau manifold that string theory
requires. Built for curious high-school and early-college audiences.

Drag to rotate the 3D stage, scroll to zoom, and step through each dimension to see how it
grows out of the one before it.

CLICK HERE TO SEE IT IN ACTION: https://damionwaltermeyer.github.io/11-dimensions/

---

## ✨ Features

- **All 11 dimensions, one at a time** — each with a live, rotatable 3D model.
- **Progressive narrative** — every description explains how that dimension is built from
  the previous one (sweep a point into a line, a line into a plane, … then curl the extras up).
- **A real Calabi–Yau manifold** — the six curled dimensions assemble into a genuine
  Calabi–Yau cross-section (computed, not hand-drawn), which builds up as you advance.
- **"Why it matters" + "Sense of scale"** notes on every dimension to anchor the intuition
  (e.g. *blow an atom up to the size of the solar system and a curled dimension would still
  be smaller than a grain of sand*).
- **Optional equations** — a per-dimension math toggle reveals a signature relation, from the
  spacetime interval to the Calabi–Yau Euler-characteristic / particle-generations link and the
  M-theory coupling–radius relation.
- **Honesty built in** — an "established vs. speculative" panel makes clear which dimensions are
  measured physics and which are required by the math but unobserved.
- **Fully interactive** — drag to rotate, scroll/pinch to zoom, keyboard arrows to step.

---

## 🚀 Deploying

This is a single, self-contained static file. **No backend, no build step, no dependencies,
no network access required** — Three.js, the runtime, and the fonts are all inlined.

### Option A — GitHub Pages
1. Commit `index.html` to the repository.
2. In **Settings → Pages**, set the source to your branch (e.g. `main`) and root (`/`).
3. Your site goes live at `https://<username>.github.io/<repo>/`.

### Option B — AWS S3 static website
1. Upload `index.html` to your bucket.
2. Enable **Static website hosting** and set the index document to `index.html`.
3. Make the object public (or front it with CloudFront).
4. *(If needed)* set the object's `Content-Type` to `text/html`.

### Option C — Offline / local
Just open `index.html` in any modern browser — double-click it, or hand it off on a USB stick.
It works with no internet connection.

---

## 🗂 Files

| File | Purpose |
|------|---------|
| `index.html` | The standalone, self-contained app. **This is all you need to deploy.** |

---

## 🖥 Requirements

- Any modern browser with WebGL (Chrome, Firefox, Safari, Edge — desktop or mobile/tablet).
- No server, no API keys, no tracking, no cookies.

---

## 🔬 A note on accuracy

The three dimensions of space and one of time are directly measured and underpin all of modern
physics. The extra dimensions are **required by the mathematics of string and M-theory, but none
has ever been detected.** Their existence, their exact number, and the precise curled-up shape
shown here all remain unconfirmed — the Calabi–Yau depicted is one illustrative example drawn from
an enormous landscape of mathematical possibilities. The 3D models are faithful *schematics*: a true
Planck-scale dimension (~10⁻³⁵ m) cannot be drawn to scale.

This guide deliberately presents the higher dimensions as **extra spatial directions curled up at
every point of space** — the mainstream physics picture — rather than the popular but inaccurate
"parallel timelines" framing.

---

## 📄 License

Released under the [MIT License](LICENSE) — you're free to use, modify, and redistribute this
work (including commercially), provided the original copyright notice and license text are
included in any copies or substantial portions. See the [`LICENSE`](LICENSE) file for the full
terms.

Copyright (c) 2026 Damion Waltermeyer

## 🙏 Credits

Created by **Damion Waltermeyer**, designed and built in collaboration with **Claude (Opus, by Anthropic)**.
Rendered with [Three.js](https://threejs.org/) (also MIT-licensed).
