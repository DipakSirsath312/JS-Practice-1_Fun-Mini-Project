# JS-Practice-1_Fun-Mini-Project
This Repository🔥 JS Practice 1_ Master JavaScript Essentials with Fun Mini Projects! 💡

# JS Practice 1 – Fun Mini Project 🎯

This project is a **JavaScript practice mini project** that demonstrates interactive DOM manipulation and animation using **GSAP**.  
The rectangle dynamically changes its background color based on mouse movement, helping understand real-time event handling and animation logic.

---

## 📌 Project Description

- A rectangle is displayed at the center of the screen.
- When the mouse moves **from left to right** inside the rectangle:
  - Left side → Color gradually changes to **Red**
  - Right side → Color gradually changes to **Blue**
- When the mouse leaves the rectangle, the color resets to **White**.
- Smooth color transitions are handled using **GSAP animation utilities**.

This project focuses on:
- Mouse events
- DOM manipulation
- Coordinate calculations
- Color mapping logic
- GSAP animations

---

## 🚀 Live Preview

Open `index.html` in your browser to see the project in action.

*(You can also deploy it using GitHub Pages for a live demo.)*

---

## 🛠️ Technologies Used

- **HTML5** – Structure
- **CSS3** – Styling and layout
- **JavaScript (Vanilla JS)** – Core logic
- **GSAP (GreenSock Animation Platform)** – Smooth animations

---

## 📂 Project Structure

JS-Practice-1_Mini-Project/
│

├── index.html      # Main HTML file

├── style.css       # Styling

├── script.js       # JavaScript & GSAP logic

└── README.md       # Project documentation

---

⚙️ How It Works

The rectangle’s position and width are calculated using getBoundingClientRect().

Mouse X-axis movement is tracked using mousemove events.

gsap.utils.mapRange() maps mouse position to RGB values:

Left half → Red intensity increases

Right half → Blue intensity increases

mouseleave event resets the color smoothly.

---
