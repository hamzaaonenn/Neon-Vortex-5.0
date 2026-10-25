# ⚡ NEON VORTEX 5.0 — Cyber Nexus Arena

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Audio](https://img.shields.io/badge/Web_Audio_API-Synthesizer-00f3ff?style=for-the-badge)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=for-the-badge)
![Offline](https://img.shields.io/badge/Offline-100%25_Supported-blueviolet?style=for-the-badge)

**NEON VORTEX** is an adrenaline-fueled, cyberpunk-themed arcade space shooter built entirely in a single, zero-dependency HTML5 file. 

Featuring procedural chiptune/synthwave tracker music synthesized in real-time via the **Web Audio API**, Matrix-style **Bullet-Time (Chrono-Warp)** mechanics, tactical enemy behaviors, and cinematic combat visual effects.

---

## 🌟 Key Features

### ⏱️ Chrono-Warp (Bullet-Time) Mode
- Slow down enemy movement and incoming bullet velocities to **32%** while retaining your ship's agile responsiveness.
- Seamlessly activates real-time **audio low-pass filter sweeps** (muffling sound into a cinematic underwater/sub-bass rumble) and an immersive temporal cyan vignette.
- Recharges passively over time and through combat takedowns.

### 🎵 Procedural Web Audio Synthwave Tracker
- **Zero external audio files**: Every laser, explosion, bassline, and drum hit is synthesized natively via the browser's Web Audio API.
- **Multiple High-Octane Soundtracks**: Switch between **Track 1: Cyber Assault (134 BPM Darksynth)** and **Track 2: Overclock Rush (142 BPM Industrial Cyberdrive)**.
- **Dynamic Boss Mode**: When a Sector Guardian spawns, the music automatically shifts to an alarming **146 BPM Double-Kick Overdrive**.
- **Beat-Synchronized Arena Pulse**: Neon gridlines and background stars subtly throb with the kick drum's heartbeat.

### 👾 Tactical Enemy Ecosystem
- **Scouts & Chasers**: Basic swarm reconnaissance drones.
- **Heavy Gunners**: Armored craft that lay down periodic suppressive plasma fire.
- **👻 Stealth Phantoms**: Cloaked assassins that remain invisible to edge radar until lunging in at high speed.
- **🛡️ Shielded Enforcers**: Frontally impervious cruisers with 180° directional energy shields that deflect incoming shots; flank them from behind or bypass them with Slow-Mo and Shockwaves!
- **💣 Mine Layers**: Tactical cruisers deploying proximity mines that can be detonated by player fire to trigger explosive chain reactions against nearby hostiles.
- **👑 Sector Guardians (Bosses)**: Colossal war machines featuring radial bullet rings, telegraphed target beams, and escalating multi-phase attacks.

### 🎬 Cinematic Visual Effects & Retro CRT Mode
- **Finishing Slow-Mo Death Camera**: Delivering the final blow to a Sector Boss triggers an impact flash frame, dynamic camera zoom, and a cascading multi-point fireworks explosion sequence.
- **Retro Arcade CRT Shader**: Toggleable scanline filter, curved glass bezel vignette, and RGB phosphor glow effect.
- **Hit Feedback**: Directional deflection sparks, floating combat damage readouts, power-up magnetic attraction, and screen shake.

### 🏆 Quests & Achievements System
- **8 In-Game Achievements** with persistent tracking and Credit (◈) rewards.
- Animated golden banners slide in upon completing feats like *First Blood*, *Chrono Master*, *Shield Breaker*, or *Boss Slayer*.
- Dedicated **Achievements & Quests Modal** accessible from the main and pause menus.

### 🚀 Hangar & Sector Progression
- **4 Unlockable Ship Skins**: Distinct handling, color profiles, and firing geometries (*Single Focus Laser*, *Twin Parallel Plasma*, *Triple Spread*, and *5-Way Void Beam*).
- **Perk Draft Cards**: Upgrade Plasma Damage, Nano Hull Shields, or Chrono Capacitors after clearing each sector.

---

## 🕹️ Controls

| Key / Input | Action |
| :--- | :--- |
| <kbd>W</kbd>, <kbd>A</kbd>, <kbd>S</kbd>, <kbd>D</kbd> or Arrow Keys | Ship Propulsion & Steering |
| **Left Click** (Hold) | Continuous Laser Fire |
| <kbd>SHIFT</kbd> or **Right Click** | **Activate Bullet-Time (Chrono-Warp)** |
| <kbd>SPACE</kbd> | EMP Shockwave (Clears all bullets & enemies) |
| <kbd>N</kbd> | Cycle Synthwave Music Tracks |
| <kbd>C</kbd> | Toggle Retro CRT Scanline Shader |
| <kbd>M</kbd> | Mute / Unmute Master Audio |
| <kbd>P</kbd> or <kbd>ESC</kbd> | Pause Menu & Achievements Overview |

---

## 🚀 Quick Start / How to Play

No installation, build steps, Node.js packages, or web server required:

1. **Clone or Download the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/neon-vortex.git
