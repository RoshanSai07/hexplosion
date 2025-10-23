# 💥 Hexplosion

**Hexplosion** is an interactive **hexagonal explosion visualisation** built entirely with **HTML Canvas** and **vanilla JavaScript**.  
Click anywhere on the screen to trigger a beautiful ripple of glowing hexagons expanding outward like a mini explosion!

![Example](example.png)

## ✨ Features

- 🧩 Dynamic hexagonal grid generation
- 💥 Ripple explosion animation on click
- 🎛️ Adjustable controls for hexagon size and ripple layers
- 🖥️ Responsive full-screen canvas rendering
- ⚙️ 100% client-side — no libraries or frameworks required

## 🧠 How It Works

When you click the canvas, a ripple of hexagons expands outward in six directions, forming layers of fading hexes.  
The animation is driven by:

- The `Hexplosion` class in `app.js`
- A simple `requestAnimationFrame()` loop that continuously redraws and fades hexes
- Configurable parameters (`radius`, `rippleSize`) that you can change in real-time from the control panel

## 🚀 Getting Started

### 1. Clone or Fork the Repository

```bash
git clone https://github.com/<your-username>/hexplosion.git
cd hexplosion
```
