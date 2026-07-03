# 🕒 Analog Clock

A simple **Analog Clock** built using **pure HTML, CSS, and JavaScript**.  
This project is created to **practice JavaScript events, functions, and DOM manipulation** without using any external libraries or frameworks.

---

## 🚀 Project Overview

The Analog Clock displays the **current system time** using rotating hour, minute, and second hands.  
It updates automatically every second using JavaScript.

This project helped me understand how JavaScript interacts with HTML and CSS in real time.

---

## 🛠️ Technologies Used

- **HTML** – Structure of the clock  
- **CSS** – Styling, positioning, and rotation of clock hands  
- **JavaScript** – Logic, time calculation, events, and functions  

---

## ✨ Features

- Real-time analog clock
- Smooth rotation of clock hands
- Uses system time
- Responsive design
- No external libraries used

---

## 📚 JavaScript Concepts Covered

This project focuses on core JavaScript fundamentals:

### ✅ Functions
- Used functions to calculate time
- Separate logic for hour, minute, and second hands

### ✅ JavaScript Events
- `window.onload` to start the clock after page loads

### ✅ Date Object
- `new Date()` to fetch current time
- `getHours()`, `getMinutes()`, `getSeconds()`

### ✅ DOM Manipulation
- `document.querySelector()` to select clock hands
- Dynamically updating styles using JavaScript

### ✅ setInterval()
- Updates the clock every 1 second

### ✅ CSS Transform
- `transform: rotate()` used with JavaScript to rotate clock hands

---

## 🧠 How It Works

1. JavaScript gets the current time using the `Date` object.
2. Time is converted into degrees:
   - Seconds → 6° per second
   - Minutes → 6° per minute
   - Hours → 30° per hour
3. JavaScript updates the rotation of clock hands using CSS transforms.
4. `setInterval()` runs the function every second to keep the clock updated.

---

## 📂 Project Structure


---

## ▶️ How to Run the Project

1. Download or clone the repository
2. Open `index.html` in any web browser
3. The analog clock will start automatically

---

## 🎯 Purpose of This Project

- Practice JavaScript basics
- Understand real-time DOM updates
- Learn how JS works with CSS transforms
- Strengthen logic using functions and events

---

## 🔮 Future Improvements

- Add digital time display
- Add dark/light mode
- Smooth animation using CSS transitions
- Show date and day

---

## 👨‍💻 Author

**Bedanand Kumar Sah**  
Learning Web Development 🚀  

---

## ⭐ Acknowledgment

This project is built for **learning and practice purposes** using core web technologies.

If you like this project, feel free to ⭐ the repository!
##Live:https://analog-clock-five-theta.vercel.app/
