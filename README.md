# 3D Sumo Arena Game 

A thrilling two-player local multiplayer 3D Sumo battle game built entirely in Python using **OpenGL** and **GLUT**. The objective is simple: push your opponent out of the ring before time runs out, but watch out—the arena shrinks as the match progresses!

---

## Features

* **OpenGL Visualization:** Fully rendered 3D graphics environment featuring textured arenas, 3D stadium walls, and dynamic animated crowds.
* **Shrinking Arena Mechanic:** The ring automatically shrinks after a set duration, ramping up the intensity.
* **Collision Physics:** Realistic player-to-player pushing and collision detection mechanics.
* **Dynamic Environment:** Visual color cues change when the match enters "Speed Up" / shrinking mode.
* **Local Head-to-Head:** Two-player controls on the same keyboard for ultimate competitive matches.

---

## Tech Stack & Requirements

* **Language:** Python[cite: 29]
* **Graphics & Windowing:** PyOpenGL, GLUT (OpenGL Utility Toolkit)[cite: 29]

### Prerequisites
Make sure you have Python installed, along with the required OpenGL libraries:
```bash
pip install PyOpenGL PyOpenGL_accelerate
