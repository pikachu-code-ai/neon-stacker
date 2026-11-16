# neon-stacker# 🟪 Neon Stack

A sleek, fast-paced arcade block-stacking game featuring vibrant neon visuals, precision timing mechanics, and satisfying visual feedback. Stack the glowing blocks as high as you can—every misaligned edge gets sliced away, making each layer harder than the last!

---

## ✨ Features

* **Precision Stacking Mechanics:** Drop moving blocks onto your tower. Any overhanging portion is cleanly sliced off, shrinking your landing area.
* **Perfect Drop Combos:** Nail consecutive aligned drops to trigger combo streaks, glowing pulse effects, and bonus points.
* **Dynamic Neon Aesthetic:** Smooth color transitions, glowing borders, and particle/slice animations set against a dark cyberpunk backdrop.
* **Cross-Device Controls:** Play effortlessly using a mouse, keyboard, or touchscreen.
* **Local High Score Tracking:** Automatically saves your personal best so you can keep chasing higher towers.
* **Lightweight & Self-Contained:** Built as a single-file web application with zero external build dependencies required to run.

---

## 🎮 How to Play

1. **Start the Game:** Click anywhere on the screen or press `Space` to begin.
2. **Drop the Block:** Watch the neon slab slide across the top of your tower and press `Space`, click, or tap when it lines up with the block below.
3. **Keep Your Balance:** 
   * **Misaligned drop:** The overhanging piece breaks off, leaving a smaller platform for the next block.
   * **Perfect drop:** The block locks in cleanly with a visual flash, preserving your platform width and building your combo multiplier.
4. **Game Over:** The run ends if a block misses the tower completely. Hit restart to beat your high score!

### Controls

| Action | Keyboard | Mouse / Touch |
| :--- | :--- | :--- |
| **Start / Drop Block** | `Space` / `Enter` | Left Click / Tap |
| **Restart Game** | `Space` / `R` | Click Restart Button |

---

## 🛠️ Tech Stack

* **HTML5** – Structure and rendering surface (`<canvas>` / DOM elements)
* **CSS3** – Neon glow effects, responsive layout, and UI styling
* **JavaScript (ES6+)** – Game loop, collision/slicing math, combo logic, and local storage persistence

---

## 💡 Ideas for Future Customization

* **Synthwave Audio:** Add Web Audio API sound effects that increase in pitch with each consecutive combo.
* **Theme Switcher:** Add selectable neon color palettes (e.g., *Cyber Pink*, *Synth Gold*, *Matrix Green*).
* **Difficulty Modes:** Introduce speed-ramp multipliers or narrower starting blocks for an extra challenge.
