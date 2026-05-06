# The Pulickal Algorithm: Topological Convergence Engine

> **"Sequential logic is an artifact of planar constraint. True intelligence is volumetric and multi-polar."**  
> — *Pearl Bipin Pulickal, The Pulickal Bible (Vol I)*

![License](https://img.shields.io/badge/License-MIT-gold.svg) ![Version](https://img.shields.io/badge/Version-2.4.0_Elite-blue.svg) ![Tech](https://img.shields.io/badge/Stack-Three.js_|_Canvas_API-00f3ff.svg)

## 🔬 Abstract

This repository contains the **Reference Implementations** for the **Pulickal Algorithm**, a multi-polar recursive convergence model designed to challenge standard linear traversal methods (such as Dijkstra's Algorithm) in high-dimensional manifolds.

The simulations demonstrate the **"Time to Saturation" (TTS)** differential between:
1.  **Linear Logic:** Single-threaded, single-origin sequential scanning ($O(N^2)$).
2.  **Pulickal Logic:** Multi-threaded, multi-origin parallel convergence ($O(\sqrt[3]{N})$).

---

## 📂 Modules

### 1. The Planar Comparator (2D)
*Located in `/2d-planar-engine/`*

A high-fidelity **HTML5 Canvas** visualization comparing wavefront propagation on a 2D grid.
*   **Visuals:** Cyber-Glass Aesthetic (Neon Blue vs. Royal Gold).
*   **Engine:** Custom `CanvasRenderingContext2D` with High-DPI/Retina scaling.
*   **The Test:** 
    *   **Left Pane:** Standard Linear Scan initiating from `[0,0]`.
    *   **Right Pane:** Pulickal Convergence initiating simultaneously from `[0,0]`, `[Max,0]`, `[0,Max]`, and `[Max,Max]`.

### 2. The Cubix Architecture (3D)
*Located in `/3d-cubix-engine/`*

A fully interactive **Volumetric Simulation** built on **Three.js**. This module visualizes the theoretical hardware architecture of "The Sponge" (Fluid-Integrated Substrate).
*   **Visuals:** Deep Space Voxel Grid with Emissive Lighting.
*   **Engine:** Dual WebGL Renderers with `OrbitControls` for 360° analysis.
*   **The Core Event:** 
    *   Demonstrates the **8-Front Convergence**, where execution threads start from all vertices of the hypercube.
    *   Triggers a **"Critical Mass"** visual event when the fronts unify at the geometric center (The Pulickal Core).

---

## 📐 Theoretical Basis

### The Convergence Factor
Conventional algorithmic traversal treats data as a "flatland," scanning line-by-line. The Pulickal Algorithm treats data as a **Volume**.

By initializing execution fronts at opposing polarities of the manifold, we achieve a theoretical speedup factor derived from the geometric reduction of travel distance to the center.

$$ T_{pulickal} \approx \frac{T_{linear}}{2^d} $$

*Where $d$ is the dimension of the space (2 for Planar, 3 for Cubix).*

---

## 🚀 Installation & Usage

This project is built with **Vanilla JavaScript** and requires no build step (Webpack/Vite) for the standard version.

### Quick Start
1.  Clone the repository:
    ```bash
    git clone https://github.com/PearlPulickal/pulickal-algorithm.git
    ```
2.  Navigate to the desired module (2D or 3D).
3.  Open `index.html` in any modern browser (Chrome/Edge/Firefox).

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

Copyright © 2026 Pearl Bipin Pulickal.
Open source for educational and research purposes. Commercial implementation of the Lightning Energy Harvesting logic or Cubix Hardware Architecture requires written consent.
