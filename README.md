
# 🚦 Traffic Flow Simulation

A simple and visually appealing traffic flow simulation built using **HTML5 Canvas**, **CSS**, and **vanilla JavaScript**. This project demonstrates basic animation, object-oriented programming, and traffic light logic in a browser environment.

---

## 📸 Preview

https://traffic-flow-simulator-mn.netlify.app/

---

## ✨ Features

* 🚗 Multiple animated cars with varying speeds and colors
* 🚦 Functional traffic light system (Green → Yellow → Red)
* ⛔ Cars stop at red lights and resume on green
* 🎮 Start and pause controls
* 📱 Responsive design for smaller screens
* 🎨 Smooth visuals with shadows and gradients

---

## 🛠️ Technologies Used

* **HTML5** – Structure and canvas element
* **CSS3** – Styling and responsive design
* **JavaScript (ES6)** – Logic, animation, and simulation

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/traffic-flow-simulation.git
```

### 2. Open the project

Simply open the `index.html` file in your browser.

---

## 🎮 How to Use

* Click **Start** ▶️ to begin the simulation
* Click **Pause** ⏸️ to stop it
* Watch how cars react to traffic light changes

---

## 🧠 How It Works

### Car System

* Each car is an object created from a `Car` class
* Cars move horizontally across the canvas
* When reaching the edge, they loop back to the start

### Traffic Light Logic

* The light cycles every ~300 frames:

  * Green → Yellow → Red → Green
* Cars check the light state before crossing the intersection

### Animation Loop

* Uses `requestAnimationFrame()` for smooth rendering
* Continuously updates:

  * Road
  * Traffic light
  * Car positions

---

## 📂 Project Structure

```
traffic-flow-simulation/
│── index.html   # Main file (HTML, CSS, JS combined)
│── preview.png  # Screenshot (optional)
```

---

## 👤 Author

**Michael Nsengiyumva**


---
