<div align="center">
<img width="315" height="250" alt="image" src="https://github.com/user-attachments/assets/c27dabd5-81dd-43a9-a335-6ddc9783d188" />


  <h1>🦖 HYPER DINO SQUARE</h1>
  
  <p>
    <strong>A Chaotic Arcade Survival Game about geometric dinos.</strong>
  </p>

  <p>
    <a href="https://godotengine.org">
      <img src="https://img.shields.io/badge/Engine-Godot%204-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Focus-Level%20Design%20%26%20Architecture-success?style=for-the-badge&logo=c-sharp&logoColor=white" />
    </a>
    <a href="https://veggi3.itch.io/hyper-monkey-square">
      <img src="https://img.shields.io/badge/Play%20on-Itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" />
    </a>
  </p>
</div>

---

## 📖 About the Project

<img width="1146" height="637" alt="image" src="https://github.com/user-attachments/assets/89d10165-ad04-4d5c-a21a-323e2f6d68be" />

**Hyper Dino Square** is a hyper-casual arcade game designed to test player reflexes within a dynamic arena. The player controls a dino that must navigate a treacherous environment where the floor itself is the enemy.

The project was built with a strong emphasis on **Scalable Architecture** and **Emergent Level Design**, ensuring that chaotic gameplay arises from the interaction of simple, modular systems.

---

## ⚙️ Engineering & Design Highlights

### 🧱 Modular Platform System (OOP)

<img width="266" height="377" alt="image" src="https://github.com/user-attachments/assets/09739fbc-4c9f-4a91-b318-e4b060f43ff2" />

Instead of hard-coding behaviors, I engineered a **Polymorphic Platform System** using inheritance and composition. This allows for rapid iteration and creation of new hazards.
* **Base Class:** Handles common logic (collision, spawning, visual state).
* **Derived Types:** specialized behaviors like `Left-to-Right`, `Right-to-Left`, `Diagonal`, `Up-Down` and `Down-Up`.
* **Benefit:** New platform types can be added in minutes by extending the base class without modifying the core game loop.

### 📐 Dynamic Level Design & Pacing
The core challenge isn't just reflexes, but **Spatial Management**. The level design evolves procedurally to force player movement.
* **Arena Constraints:** The confined 4x4 (or NxN) grid forces players to think several steps ahead, creating a "Risk vs. Reward" dynamic when chasing collectibles.
  
---

## 🕹️ How to Play

* **Objective:** Survive as long as possible while the floor disappears and changes under your feet.
* **Controls:**
    * **PC:** `Arrow Keys` or `A D` to dash.

---

## 🛠️ Credits & Tools

* **Developer:** Matheus Soares ([@MrVeGGi3](https://github.com/MrVeGGi3))
* **Engine:** Godot 4
* **Art Assets:** Custom Pixel Art created in Aseprite.

---

<div align="center">
  <p><i>Developed with 💙 by Veggi3</i></p>
</div>
