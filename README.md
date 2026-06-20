# Frontier RTS - Command Upgrade

**Frontier RTS** is a lightweight, browser-based HTML5 Real-Time Strategy game. Command your units, establish supply lines, and conquer an AI opponent on a procedurally generated map. 

Play the game directly in your browser here: **[Insert Your GitHub Pages Link Here]**

![Frontier RTS Gameplay](https://img.shields.io/badge/Status-Playable-brightgreen.svg)
![HTML5 Canvas](https://img.shields.io/badge/Tech-HTML5%20Canvas-orange.svg)
![Vanilla JS](https://img.shields.io/badge/Tech-Vanilla%20JS-yellow.svg)

## 🌟 Features
* **No Dependencies:** Built entirely in a single file using vanilla JavaScript, HTML5 Canvas, and CSS.
* **Procedural Map Generation:** Every game features a unique 256x256 map with distinct biomes (Grass, Forests, Mountains, and Water).
* **Supply Line Mechanics:** Expand your territory by linking captured buildings within a 64-tile radius of your Headquarters.
* **Dynamic AI Opponent:** Face off against a smart AI with different randomly assigned personas (Expansionist, Raider, Fortress, Hunter).
* **HD 2D Rendering:** Experience smooth 60fps gameplay with dynamic drop-shadows, animated HD building sprites, rotating multi-part vehicles, and interactive move-rings.
* **Fog of War & Intel:** Use Drones and Radar Arrays to peel back the fog and pinpoint the enemy HQ.

## 🎮 How to Play

### Controls
* **Left Click:** Select units (click and drag to box-select multiple units).
* **Right Click:** Order selected units to move or attack a target.
* **Spacebar or 'H':** Instantly snap the camera back to your Headquarters.
* **Edge Scrolling / Mouse:** Move the mouse to the edges of the screen to pan the camera, or click on the tactical minimap.

### Gameplay Loop
1. **Build Your Economy:** You start with an HQ, 100 Funds, and +10 Funds/sec. Use your starting units to explore the map and capture nearby neutral **Villages** and **Factories** to increase your income.
2. **Chain Your Supply:** Buildings only generate income and repair themselves if they are within 64 tiles of another connected building, tracing all the way back to your HQ.
3. **Neutralize & Capture:** To capture an enemy or neutral building, you must first neutralize its HP using Tanks or Infantry. Once neutralized (yellow HP bar), move Infantry close to the building to capture it.
4. **Upgrade:** Find and capture a **Lab** to unlock devastating Heavy Tanks.
5. **Win:** Locate, neutralize, and capture the Enemy HQ.

## 🗺️ Terrain Guide
Terrain heavily affects movement speed and tactical positioning:
* 🟩 **Grass:** 100% Movement Speed.
* 🌲 **Forest:** 70% Movement Speed. Buildings can spawn here.
* ⛰️ **Mountain:** 30% Movement Speed. Heavy natural chokepoints.
* 🌊 **Water:** 30% Movement Speed. 

*(Note: Units receive a 25% speed boost when pathing inside their own supply influence zones!)*

## 🛠️ Installation / Running Locally
Because this game is entirely client-side, no installation or server is required. 
1. Clone or download this repository.
2. Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Enjoy!

## 📜 License
This project is open-source and free to use, modify, and distribute."# TinyRTS" 
