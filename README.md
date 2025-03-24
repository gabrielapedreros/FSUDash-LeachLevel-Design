# FSUDash – Leach Level Design

In my **CEN4020L Capstone** course, our group developed a game using the **PyArcade** tutorial. We chose **Tiled** for level design and leveraged **AI** to assist with generating assets and layouts.

---

## Creating the Tilemap Using AI

My level was set in **The Leach**, the main gym at FSU. I worked with AI to generate a tiled map based on photos of the gym.

- I provided images of The Leach and instructions to the AI.
- The AI generated a 2D background image: `gym.png`.
- This image became the base I used to extract tiles for my level.
- I also created `tileset.png`, a tilemap featuring gym equipment.

---

## Designing My Level

### Creating Tilesets

Using the base images, I created the tilesets for the game:

- `gym.png` → `gym.tsx` (main tileset for the background)
- `tileset.png` → `tileset.tsx` (equipment tiles used for gameplay elements)

### Creating Layers in Tiled

I used both **Tile Layers** and **Object Layers**:

- **Tile Layers**:  
  - `Background`  
  - `Platform`  
  - `Coins` (represented using gym equipment tiles)

- **Object Layers**:  
  - `Player`  
  - `Enemy`

---

## Character Assets

- **Player**: AI-generated image `player.jpg`
- **Enemy**: Open-source image `scarytiger.png`

---

## Power-Ups

- Gym equipment tiles (like weights) were repurposed as **power-ups** (similar to coins).

---

## Final Tilemap

The completed level design was exported as:

- `level3final.tmx`

This tilemap was integrated into our PyArcade project as a json file and we continued from there. 

---
