# 🏁 Turbo Nights

> A love letter to the classic 8-bit arcade racers of the 80s. Strap in and accelerate through nocturnal highways in a pseudo-3D environment, face off against relentless AI-driven rivals, and burn nitrous under neon lights. 

Built entirely from scratch without any external engines or libraries, **Turbo Nights** delivers pure high-speed action powered solely by Vanilla JavaScript, the HTML5 Canvas API, and procedural chiptune audio.

*Developed with passion by **Bryan_Ponciano**.*

---

## 🌟 Overview

Turbo Nights puts you behind the wheel of a high-performance sports car across retro-futuristic landscapes. Battle against 7 aggressive AI-driven rivals, manage your car's degradation, blast through nitrous boosts at the perfect moment, and secure your lap records in the Hall of Fame.

## 🚀 Key Features

* **Pseudo-3D Track Projection:** Classic raster scanline rendering that perfectly simulates road curves, perspective scaling, and dynamic vertical hill elevations.
* **6 Handcrafted Stages & Themes:**
  * 🏙️ **Neon City:** Downtown skyscrapers under deep emerald and indigo lights.
  * 🌅 **Sunset Bay:** Coastal highway during a retro synthwave sunset.
  * 🏜️ **Desert Run:** High-speed canyon turns flanked by saguaro silhouettes.
  * 🌐 **Cyber Grid:** Futuristic overpass glowing with cyan and magenta neon grids.
  * ⛈️ **Black Sea:** Stormy ocean highway under deep midnight mist.
  * 🌋 **Inferno Run:** High-intensity volcanic touge mountain pass.
* **Synthesized Chiptune Audio:** Procedural music and sound effects (revving engine, drifts, nitro, collisions, and lap chimes) generated in real-time via the browser's Web Audio API.
* **Damage Physics & Quick Respawn:**
  * Collisions reduce your vehicle's condition (POWER).
  * Heavy damage triggers engine smoke and eventual catastrophic breakdown.
  * Quick respawn allows instant recovery directly at your current track position while competitors keep racing.
* **Traffic AI:** 7 dynamic opponents featuring lane-switching, slipstream drafted overtakes, and cornering speed modulation.
* **Hall of Fame:** Local driver tag identification and leaderboard persistence powered by `localStorage`.

## 🎮 Controls

| Action | Key(s) |
| :--- | :--- |
| **Steer Left / Right** | `←` / `→` or `A` / `D` |
| **Accelerate** | `↑` or `W` |
| **Brake / Slow Down** | `↓` or `S` |
| **Nitrous Turbo** | `SPACE` |
| **Quick Respawn (When Wrecked)** | `R` or `SPACE` |
| **Hall of Fame (Leaderboard)** | `H` |
| **Change Pilot Tag** | `U` *(on title menu)* |
| **Pause / Resume** | `P` |
| **Mute / Unmute Audio** | `M` |
| **Toggle Fullscreen** | `F` |

## 🛠️ Tech Stack

* **JavaScript (ES6+):** Pure vanilla code powering game loops, vector math, physics, and opponent AI.
* **HTML5 Canvas 2D:** Low-resolution (256x224) pixel-art rendering scaled with crisp nearest-neighbor interpolation (`image-rendering: pixelated`).
* **Web Audio API:** Procedural oscillator-based multi-channel sound synthesizer (zero heavy `.mp3` or `.wav` assets).
* **CSS3:** Responsive aspect-ratio scaling and CRT arcade framing.

## 📦 How to Play

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/your-username/turbo-nights.git](https://github.com/your-username/turbo-nights.git)
