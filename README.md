# Liquid-Matter-Touch-Driven-Chaos
A dual-canvas particle system with mouse-driven force and dynamic line connections.
# 🌌 LiqMatter: Interactive Particle Flow

**LiqMatter** is a dual-canvas particle simulation built with vanilla JavaScript and HTML5 Canvas. It features mouse-driven force interactions, dynamic line connections, and friction-based motion—all rendered in real time with elegant visual polish.

---

## 🎯 Features

- 🖱️ **Mouse Interaction**  
  Press and drag to push particles away with force-based motion.

- ⚛️ **Particle Physics**  
  Each particle responds to velocity, friction, and boundary collisions.

- 🧵 **Dynamic Connections**  
  Particles within proximity connect with fading lines based on distance.

- 🖼️ **Dual Canvas Rendering**  
  Visual separation of particle bodies and connection lines for layered effects.

- 📐 **Responsive Design**  
  Automatically resizes to fit any screen dimensions.

---

## 🧠 How It Works

- **Canvas Setup**: Two canvases (`canvas1` and `canvas2`) handle particles and connections separately.
- **Particle Class**: Each particle has position, velocity, friction, and push vectors.
- **Mouse Events**: `mousedown`, `mousemove`, and `mouseup` control interaction radius and direction.
- **Connection Logic**: Particles within `maxDistance` draw lines with opacity based on proximity.
- **Resize Handling**: On window resize, particles reset and canvases adjust dimensions.

---

## 🛠️ Technologies

- HTML5 Canvas API  
- Vanilla JavaScript (no external libraries)  
- Responsive event-driven architecture

---

## 📁 File Structure
LiqMatter/ ├── index.html ├── style.css  └── script.js


---


## 📌 To Do

- [ ] Add touch support for mobile devices  
- [ ] Toggle line connections on/off  
- [ ] Add color gradients or particle trails  
- [ ] Host live demo on GitHub Pages

---


## 📜 License

MIT License. Feel free to fork, remix, and build on it.

---

## 🙌 Author

**Shubhanjali**  
Passionate about interactive visuals, game mechanics, and creative coding.
