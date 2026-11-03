# 🏍️ CYBER HIGHWAY: WRONG WAY

![Version](https://img.shields.io/badge/SYS.VER-2099.4.2-00f3ff?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-r128-ff007f?style=for-the-badge&logo=threedotjs)
![HTML5](https://img.shields.io/badge/Single--File-HTML5%20%2F%20JS%20%2F%20CSS-fcee09?style=for-the-badge&logo=html5)

**CYBER HIGHWAY: WRONG WAY** is a fast-paced 3D Cyberpunk endless arcade highway game built with **Three.js**, **Tailwind CSS**, and the **Web Audio API**. Pilot a 2099 Light-Cycle head-on against four lanes of oncoming megacity traffic, chain together high-risk **Near Miss Combos**, and unleash **Nitro Overdrive** across a neon-drenched synthwave expressway.

---

## ✨ Key Features

- **3D Cyberpunk Highway Environment**:
  - Procedural megacity skyline with glowing neon window strips and roof beacons.
  - Overhead neon toll gantries, cyber-grid floor, CRT scanline overlay, and a retro synthwave horizon sun.
- **2099 Light-Cycle Physics & Themes**:
  - Smooth lateral steering with dynamic motorcycle lean/tilt physics and twin plasma exhaust thrusters.
  - 3 selectable neon color themes on the start screen: **Cyber Cyan**, **Synth Pink**, and **Solar Gold**.
- **Oncoming Traffic Archetypes**:
  - **Cyber Sedans**: Agile oncoming city cruisers that occasionally switch lanes.
  - **Heavy Cargo Trucks**: Massive armored haulers with wide hitboxes and yellow fog beams.
  - **Cyber Police Interceptors**: High-speed pursuit units with flashing red-and-cyan roof sirens.
- **Near Miss Combo System**:
  - Brush closely past oncoming vehicles without crashing to trigger **NEAR MISS** popups, build your score multiplier, and recharge your Nitro tank.
- **Nitro Overdrive (`2X Boost`)**:
  - Doubles your active score multiplier, widens camera FOV for an intense sense of speed, and ignites magenta plasma exhaust trails.
- **Plasma Shields & Highway Power-Ups**:
  - Equipped with **3 Plasma Shields** that absorb head-on collisions and trigger a localized 3D voxel EMP explosion.
  - Collect floating **Shield Orbs** (`+1 Shield`) and **Nitro Cells** (`+45% Nitro`) along the highway.
- **Dual Camera Modes**:
  - Instantly switch between **Third-Person Chase Cam** and **First-Person Helmet Visor Cam**.
- **Minimalist Mobile HUD & Multi-Touch Navigation**:
  - Ultra-compact top and bottom HUD strips designed to keep the horizon and oncoming traffic completely unobstructed on mobile screens.
  - Symmetrical **`[ ◀ LEFT ] [ NITRO ] [ RIGHT ▶ ]`** bottom control bar with independent multi-touch tracking so you can steer and boost simultaneously.
- **Procedural Web Audio Synthesizer**:
  - Built-in real-time sound engine generating dynamic motorcycle engine RPM pitch, Doppler near-miss chimes, power-up arpeggios, and crash impacts with zero external audio files required.

---

## 🎮 Controls

### Desktop (Keyboard & Mouse)
| Input | Action |
| :--- | :--- |
| **`A` / `D`** or **`◀` / `▶` Arrow Keys** | Steer Left / Right |
| **`Space`** / **`Shift`** / **`W`** / **`▲`** | Hold to activate **Nitro Overdrive (2X)** |
| **`C`** | Switch Camera View (*Chase Cam* / *Helmet Cam*) |
| **`M`** | Mute / Unmute Procedural Audio |
| **Mouse Click + Drag** | Look around dynamically while riding |

### Mobile / Touch Devices
| On-Screen Control | Action |
| :--- | :--- |
| **`[ ◀ LEFT ]`** (Bottom Left) | Hold to steer left |
| **`[ NITRO ]`** (Bottom Center) | Hold to engage **Nitro Overdrive (2X)** |
| **`[ RIGHT ▶ ]`** (Bottom Right) | Hold to steer right |
| **Camera / Speaker Icons** (Top Right) | Toggle Camera Mode or Mute Audio |

---

## 🚀 Getting Started

Because the entire game is self-contained in a single HTML file with zero local asset dependencies, running it takes seconds:

1. Download or clone the repository containing `cyber_tol_lawan_arus.html`.
2. Open `cyber_tol_lawan_arus.html` directly in any modern desktop or mobile web browser (Chrome, Edge, Firefox, Safari).
3. Select your preferred **Light-Cycle Neon Theme** and click **RIDE INTO TRAFFIC**.

> **Tip:** Your highest score is automatically saved in your browser via `localStorage` (`cybertol_highscore`).

---

## 🛠️ Tech Stack

- **3D Rendering**: [Three.js (r128)](https://threejs.org/) (`WebGLRenderer`, procedural geometries, dynamic FOV, fog, and particle systems)
- **UI & Styling**: [Tailwind CSS](https://tailwindcss.com/) + Custom Cyberpunk CSS (`clip-path` angled panels, CRT scanlines, neon text glows)
- **Typography & Icons**: Google Fonts (`Orbitron` & `Rajdhani`) and [Font Awesome 6](https://fontawesome.com/)
- **Audio Engine**: Native HTML5 **Web Audio API** (`OscillatorNode`, `BiquadFilterNode`, and procedural noise buffers)

---

## 📜 License

This project is open-source and free to use for learning, customization, and arcade fun.
