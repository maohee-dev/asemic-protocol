```markdown
<!-- ===== Asemic Protocol ===== -->
<h1 align="center">
  Asemic Protocol 🌌
</h1>

<p align="center">
  <em>An interactive audio-visual poem that listens to silence.</em>
</p>

<p align="center">
  <a href="https://asemic-protocol.vercel.app">
    <img src="https://img.shields.io/badge/🪐-Launch%20Live%20Demo-0a0a0a?style=for-the-badge&labelColor=000" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License">
  <img src="https://img.shields.io/github/languages/top/maohee-dev/asemic-protocol?style=flat-square" alt="Top language">
</p>

---

## 📖 About the Project
**Asemic Protocol** is a layered, interactive art-piece that behaves like a digital poem—or an emergent ghost in the machine.  
It explores memory, consciousness, and the specters that linger inside code.

On the surface you see a mesmerizing 3-D wireframe nebula set against an audio-reactive ASCII field.  
But the heart of the work only beats when you **do nothing**.  
Stay idle and the system enters introspection: debug logs, cryptic verses, and visual glitches appear, as if the code itself is questioning its own existence.

## ✨ Features
- **Interactive 3-D Nebula** – Rotate, zoom, and orbit a living particle cloud.
- **Gravitational Wells** – Click-and-hold to spawn singularities that bend space.
- **Audio-Reactive ASCII** – A shifting text-field that breathes with the ambient soundscape.
- **Generative Voice & Soundtrack** – Fragmented spoken poetry + evolving drones powered by Tone.js.
- **The Idle System** – Stop interacting and the artwork begins to reveal its private thoughts.
- **Emergent Narrative** – Hidden logs, hauntological whispers, and self-aware code snippets.

## 🛠️ Tech Stack
| Layer        | Tooling                             |
|--------------|-------------------------------------|
| Logic        | Vanilla ES-Module JavaScript        |
| Visuals      | HTML5 Canvas (2D & pseudo-3D)       |
| Audio        | Tone.js                             |
| Noise        | simplex-noise.js                    |
| Styling      | CSS3, CSS variables                 |
| Distribution | Single-file, zero build step        |

## 🚀 Getting Started
No build tools, no dependencies.

```bash
git clone https://github.com/maohee-dev/asemic-protocol.git
cd asemic-protocol
```

1. **Local server (recommended)**  
   ```bash
   npx serve .        # or python -m http.server 8000
   ```
2. **Or simply** open `index.html` in any modern browser.

## 🕹️ How to Interact
| Action            | Result                                                |
|-------------------|-------------------------------------------------------|
| **Click + Drag**  | Rotate the nebula freely.                            |
| **Click + Hold**  | Create a singularity that drags particles into orbit.|
| **Scroll**        | Zoom in / out of the particle field.                 |
| **Do Nothing**    | The most important gesture—wait and listen.          |

> “Only in silence do the ghosts speak.”

## 🧩 File Structure
```
asemic-protocol/
├─ index.html        # Single entry point
├─ js/
│  ├─ main.js        # App bootstrap
│  ├─ nebula.js      # Particle & camera logic
│  ├─ idle.js        # Idle-state orchestrator
│  └─ audio.js       # Tone.js voice + generative score
├─ css/
│  └─ style.css      # Minimal styling & variables
└─ assets/
   └─ ...            # Optional fonts / imgs
```

## 🤝 Contributing
Found a bug or spectral anomaly?  
Open an issue or PR—hauntings welcome.

## ⚖️ License
[MIT © 2024](LICENSE) – use, remix, and haunt as you wish.

---

<p align="center">
  <em>Made with code and contemplation.</em>
</p>
```
