# Abdelrahman Shaaban

I build things that run in a browser tab and try to feel like more than a browser tab —
real-time WebGL, procedural geometry, and live data, usually with no build step at all.

**[shaaban-six.vercel.app](https://shaaban-six.vercel.app)** · **[@shaaban\_\_ai](https://www.instagram.com/shaaban__ai/)**

---

### 🌍 [Our Beautiful Planet](https://github.com/amrbody71-commits/our-beautiful-planet)

[![Our Beautiful Planet](https://raw.githubusercontent.com/amrbody71-commits/our-beautiful-planet/main/docs/hero.jpg)](https://our-beautiful-planet.vercel.app)

A spinning Earth carrying **284 live webcams across 53 countries**. Hover a pin and you see
what is happening there right now. The globe is lit from the real subsolar point, so the
cameras that are genuinely in darkness read as dark — that is the whole idea, not a decoration.

Geographic correctness is asserted against the *real Earth* rather than against the app,
after a mirrored-world bug once stayed perfectly self-consistent through every internal check.

`WebGL2` · `three.js` · `GLSL` · `Natural Earth` · `NASA Black Marble` · no build step

**[Live →](https://our-beautiful-planet.vercel.app)**

---

### 𓂀 [DUAT](https://github.com/amrbody71-commits/duat)

A scroll-driven descent into the Egyptian underworld. The sun sets over Giza, you fall
through the bedrock into the Hall of Two Truths where your heart is weighed against a
feather, and you climb back out at dawn.

The pyramids, dunes, sky, river, hall and the extruded `DUAT` wordmark are **all procedural
geometry** — written in code, not modelled. One HTML file, no bundler, no `node_modules`.

My first website.

`three.js` · `GLSL` · `procedural geometry` · `ACES filmic` · single file

**[Live →](https://duat-phi.vercel.app)**

---

### عُمر [OMR](https://github.com/amrbody71-commits/omr)

A scroll-driven descent through a life. Photographs hang as glass lanterns on a helix
falling away into the dark, a thread of light runs down the axis lit only as far as you
have travelled, and the colour of the world shifts as you pass through the years.

Volumetric ink boils off the thread — a `GPUComputationRenderer` FBO pair advecting up to
**36,864 particles entirely on the GPU**, each one keeping the colour of the year it was
born into.

The album is a private family one, so the repository publishes **the engine and the
pipeline, not the photographs**. It ships with a placeholder album so a clone still runs.

`three.js` · `GPGPU` · `GLSL` · `fal` depth pipeline

---

### Also in here

| | |
|---|---|
| **Timeport** | AI-generated 360° panoramas of places that no longer exist, from historically-researched prompts |
| **Empty Skies** | Middle East airspace during the closure, read out of OpenSky flight data |
| **style.** | I photographed my wardrobe and built something that dresses me from it, learning from feedback |
| **Jumu'ah Manchester** | Prayer times, for people who need them |

Some of these are still private while I clean them up.

---

<sub>Most repositories here are working notebooks rather than finished products, and the
few that are public say honestly what they do not do. The globe's README has a *Known gaps*
section for a reason.</sub>
