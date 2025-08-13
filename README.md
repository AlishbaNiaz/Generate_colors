# Generate_colors
# 🎨 Random Background Color Generator

This project is a simple HTML + JavaScript application that generates a **random background color** when the user clicks a button. The RGB color code is also displayed dynamically on the screen.

## 📌 Features
- **Generates a random color** each time the button is clicked.
- Displays the **RGB value** of the generated color in real time.
- Changes the background color of the container (`div`) dynamically.
- Simple, responsive design with centered text.

## 🛠️ Technologies Used
- **HTML5**
- **CSS3** (for styling button, layout, and container)
- **JavaScript** (for DOM manipulation and random color generation)

## 🚀 How It Works
1. A `click` event listener is added to the **Generate color** button.
2. On each click:
   - Random values are generated for **red**, **green**, and **blue** channels using `Math.random()` and `Math.floor()`.
   - The `<h1>` element displays the `rgb()` value.
   - The background color of the container `<div>` changes to the new color.

## 📂 How to Run
1. Save the file as `index.html`.
2. Open it in any modern web browser.
3. Click the **Generate color** button to see the background change.

## 🎯 Learning Purpose
This mini-project demonstrates:
- DOM selection (`document.querySelector`)
- Event handling (`addEventListener`)
- Random number generation
- Dynamic style updates with JavaScript

---
