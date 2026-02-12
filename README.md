# 🎲 Housie Game (Tambola Web Application)

A fully interactive two-player Housie (Tambola) game built using **HTML, CSS, and Vanilla JavaScript**.

This project simulates a real-world Tambola game with automated number generation, dynamic ticket creation, and real-time winner detection.

---

## 🚀 Live Features

- 🎯 Two Player Game Mode
- 🔢 Random Number Generator (1–100, no repetition)
- 🎫 Auto-Generated Housie Tickets
- 🟢 Real-time Number Highlighting
- 🏆 Automatic Winner Detection
- 🔍 “Check if Number is Over” Feature
- 🔄 New Game / Restart Option
- 💻 Desktop Optimized UI
- 🎨 Interactive UI with Blur Alerts for Mobile

---

## 🧠 Game Logic Overview

### 🎟 Ticket Generation
- Each player gets a dynamically generated ticket.
- Numbers are distributed column-wise (1–10, 11–20, ..., 91–100).
- Random empty slots are inserted to mimic real Tambola tickets.
- Both players get balanced ticket structures.

### 🔢 Number Generation
- Numbers from **1 to 100** are generated randomly.
- No number repeats.
- Numbers are stored and tracked in a completed list.

### 🟢 Selection Logic
- When a called number matches a ticket cell:
  - The cell is highlighted.
  - It gets marked as selected.
  - Winner logic is triggered automatically.

### 🏆 Winner Detection
- Compares:
  - Total available numbers in ticket
  - Selected numbers count
- If all required numbers are selected → Winner popup appears.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| HTML5 | Structure |
| CSS3 | Styling & UI |
| JavaScript (ES6) | Game Logic |
| DOM Manipulation | Interactive Elements |

---

## 📂 Project Structure

