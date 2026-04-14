# 🕹️ Neon Hearts: Crystal Mission

**Neon Hearts** is a retro-futuristic arcade experience built with HTML5, CSS3, and JavaScript. It revives the classic "Brick Breaker" mechanics with a vibrant neon aesthetic, dynamic physics, and multi-layered challenges.

---

## 🚀 Features

* **Progressive Level Design:**
    * **Level 1 (Hearts Mission):** The classic introduction to crystal shattering.
    * **Level 2 (Rotating Hearts):** Introducing rotating targets that require precise timing.
    * **Level 3 (The Final Challenge):** Advanced "Color Match" mechanics where players must sync the paddle color with the ball while dealing with shrinking paddles and increasing speeds.
* **Immersive Visuals:** Neon glow effects, blur filters, and a mouse-reactive parallax background.
* **Modern UI:** Integrated with **SweetAlert2** for stylized, non-intrusive game notifications and instructions.
* **Dual Control Support:** Playable via **Mouse** or **Keyboard**.

---

## 🎮 How to Play

### Basic Controls
* **Move:** Use your **Mouse** or **Left/Right Arrow Keys**.
* **Start:** Click the **Start** button or press **ENTER**.
* **Pause:** Press **SPACEBAR** to toggle pause.

### Level 3 Special Mechanics
In the final stage, you must match the ball's color to catch it:
* **Press UP Arrow (↑):** Sets paddle to <span style="color:#00f2ff">**BLUE**</span>.
* **Press DOWN Arrow (↓):** Sets paddle to <span style="color:#ff00ff">**PINK**</span>.
* **Warning:** Catching the ball with the wrong color results in an immediate Game Over!

---

## 🛠️ Tech Stack

* **Frontend:** HTML5 (Canvas API), CSS3 (Flexbox, Animations).
* **Scripting:** JavaScript (ES6+), jQuery.
* **Libraries:** * [SweetAlert2](https://sweetalert2.github.io/) - Beautiful popup boxes.
    * [Google Fonts](https://fonts.google.com/specimen/Orbitron) - Orbitron typography.

---

## 📂 Project Structure

```text
├── index.html          # Main Menu (Mission Selection)
├── c1.html             # Level 1 Logic
├── c2.html             # Level 2 Logic
├── c3.html             # Level 3 Logic
├── img/                # UI Assets and Parallax Backgrounds
└── img_srce/           # Crystal Heart Sprite Assets (s1.png - s4.png)
