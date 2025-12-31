<h1 align="center">
  🧊 cube3D
</h1>

<p align="center">
  <b>A minimal 3D raycasting engine inspired by Wolfenstein 3D</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Graphics-miniLibX-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Project-42-black?style=for-the-badge"/>
</p>

---

<p align="center">
  <i>
    Turning a 2D map into a 3D world using mathematics, rays, and pixels.
  </i>
</p>

---

## ✨ Overview

**cube3D** is a lightweight **3D raycasting engine** written in **C**, built as part of the 42 curriculum.  
It renders a **pseudo-3D environment** from a 2D map by simulating how rays interact with walls, creating depth, perspective, and immersion.

The project focuses on:
- Low-level graphics
- Mathematical precision
- Real-time rendering
- Smooth player movement and animation

---

## 🎮 Visual Concept


From a simple **2D grid**, cube3D projects a **3D scene** using raycasting and perspective correction.

---

## 🌀 Features

- 🎯 Real-time **raycasting**
- 🧭 Player rotation and smooth movement
- 🖼️ Wall textures with depth perspective
- 🌈 Floor & ceiling coloring
- ⏱️ Responsive rendering loop
- 🎥 3D illusion with dynamic view updates

---

## 🧠 How It Works (High-Level)

1. A ray is cast for each vertical screen column  
2. The ray checks wall intersections in the 2D map  
3. Distance is calculated and corrected (fish-eye fix)  
4. Wall height is projected based on distance  
5. The scene is redrawn every frame to simulate motion  

> Simple math → powerful 3D illusion

---

## 🛠 Tech Stack

- **C**
- **miniLibX**
- Trigonometry
- Vector math
- Real-time rendering loop

---

## 🎥 Animation & Movement

- Smooth camera rotation
- Forward / backward movement
- Real-time perspective updates
- Continuous redraw for fluid animation

This creates a **living 3D space** from static data.

---

## ▶️ Controls (example)

| Key | Action |
|----|-------|
| `W / S` | Move forward / backward |
| `A / D` | Strafe left / right |
| `← / →` | Rotate camera |
| `ESC` | Exit |

---

## 🚧 Project Status

✔ Core features implemented  
✔ Rendering & movement working  
✔ Fully compliant with 42 requirements  

---

## 📌 Why cube3D Matters

cube3D is not about graphics libraries —  
it’s about **understanding how 3D works under the hood**.

This project demonstrates:
- Strong mathematical thinking
- Low-level graphics control
- Real-time systems programming
- Performance-aware C code

---

## 🧊 Final Note

> cube3D proves that even simple algorithms can create immersive worlds  
> when math, logic, and creativity come together.

---
