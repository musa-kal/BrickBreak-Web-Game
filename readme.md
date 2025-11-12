# 🧱 Brick Break - Customizable Sandbox Edition

**Author:** Musa Kaleem  
**Built with:** HTML, CSS, and Vanilla JavaScript  

---

## 🎮 Overview

**Brick Break** is an interactive browser-based **sandbox game** inspired by the classic *brick breaker* arcade experience - but reimagined with full player customization.  
Everything from the **rules**, **inputs**, and **game mechanics** can be adjusted live through intuitive **buttons**, **sliders**, and **toggles**.

The project is built **entirely from scratch** using **HTML**, **CSS**, and **JavaScript**, without relying on external game engines or physics libraries.  
Every aspect - including rendering, input handling, and **collision detection** - was manually implemented for a deep, educational look into 2D game physics and DOM-based animation.

---

## 🧩 Features

### 🕹️ Sandbox Customization
Players can modify all aspects of gameplay through the settings panel:
- **Ball Velocity** - adjust speed via a slider.
- **Paddle Speed** - fine-tune movement responsiveness.
- **Brick Layout** - change number of rows and columns (1–30 rows, 1–50 columns).
- **Colors** - customize **paddle**, **ball**, and **bricks** using RGB values.
- **Input Modes** - toggle between **button** and **slider** controls.
- **God Mode** - play endlessly without losing lives.
- **Pause/Resume** - full control over game flow.
  
All adjustments apply after pressing the **RESET** button.

---

## ⚙️ Technical Highlights

### 🔢 From-Scratch Collision Detection
No libraries - all **collision physics** are implemented manually in JavaScript:
- `topCollision()`, `bottomCollision()`, `leftCollision()`, and `rightCollision()` functions handle all collision directions.
- Ball reflection logic adjusts both **X** and **Y** velocity components.
- Works for **paddle**, **bricks**, and **game borders**.

### 💻 DOM-Based Rendering
- All visuals (ball, paddle, bricks) are rendered using **SVG elements** dynamically created and positioned via JavaScript.
- The game loop runs on an optimized **`setInterval` frame update** system.

### 🎨 Responsive Design
- Fully functional on desktop and mobile browsers.
- UI adapts to screen size - ideal for touch input and mouse control.
- Built using **Bootstrap 5** for simple responsive layouting.

---

## 🧠 Implementation Files

| File | Description |
|------|--------------|
| `index.html` | Game structure and user interface (buttons, sliders, layout). |
| `main.css` | Styling for all game components and UI panels. |
| `gameLogic.js` | Core game logic, physics, and event handling (written from scratch). |

---

## 🚀 How to Run

1. Download or clone the repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
3. Press **“START GAME”** and enjoy!
4. Use on-screen controls or arrow keys (⬅️ ➡️) to move the paddle.
5. Experiment with settings and watch the gameplay evolve dynamically.

---

## 🧑‍🔬 Educational Value

This project demonstrates:
- **Game loop structure** using pure JavaScript.
- **Collision detection logic** for rectangles and circles.
- **State management** using custom objects (`ball`, `paddle`, `bricks`, `system`).
- **Dynamic DOM manipulation** and SVG rendering.
- **Responsive UI** and input versatility (touch, keyboard, slider).

---

## 🏁 Future Ideas
- Add sound effects for collisions.
- Power-ups and new brick types.
- Save custom presets for rules.
- Local high score tracking.

---

## 🧾 License
© 2024 Musa Kaleem.  
Created for educational and entertainment purposes.  
Feel free to modify or extend the project for personal learning!

---

> 💡 *“The fun isn’t just in playing - it’s in breaking the rules you create yourself.”*
