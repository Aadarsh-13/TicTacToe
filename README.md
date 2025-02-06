# TicTacToe

# 🎮 Tic-Tac-Toe Game

A simple **Tic-Tac-Toe game** built using **HTML, CSS, and JavaScript**. This game allows two players to take turns marking spaces in a 3×3 grid to get three in a row.

---

## 🚀 Features

✔️ **Two-player mode** (Player X vs. Player O)  
✔️ **Interactive UI** with a smooth gaming experience  
✔️ **Game reset option** for replaying multiple rounds  
✔️ **Win detection & Draw condition handling**  
✔️ **Minimalist design with responsive layout**  

---

## 🎯 How to Play
1. The game starts with **Player O** making the first move.
2. Players take turns clicking on an empty box to place their **X** or **O**.
3. The first player to get **three in a row (horizontally, vertically, or diagonally)** wins the game!
4. If all boxes are filled and no player wins, it's a **Draw**.
5. Click the **Reset Game** button to play again.

---

## 🛠️ Technologies Used
- **HTML** - Structure of the game  
- **CSS** - Styling and layout  
- **JavaScript** - Game logic, win conditions, and UI updates  

---



## 📜 Code Explanation

### 🔹 `index.html`
This file contains the **game structure**:
- A **3x3 grid** for the game board
- A **message container** to display winners
- **Buttons** for "New Game" and "Reset Game"

### 🔹 `style.css`
Handles the **visual styling**:
- Game layout and grid styling
- Button styles
- Responsive design for different screen sizes

### 🔹 `app.js`
Implements the **game logic**:
- Tracks player turns (`X` and `O`)
- Checks for **winning conditions**
- Displays **winner message**
- Handles **reset** and **new game** functionality

---

## 🎮 Screenshots

![image](https://github.com/user-attachments/assets/e326ed30-82fb-498a-a97a-b1d8a1f34259)

---


 
---

## 🏃‍♂️ How to Run  

### ✅ **Method 1: Open Directly in Browser (Easiest)**  
1. **Download the project files** or clone the repository.  
2. Locate the `index.html` file in your project folder.  
3. **Double-click** `index.html`.  
4. It will open in your **default web browser**.  
5. Start playing! 🎮  

---

### ✅ **Method 2: Use Live Server in VS Code (Recommended)**  
1. **Install VS Code** → [Download VS Code](https://code.visualstudio.com/)  
2. Open the project folder in VS Code.  
3. **Install Live Server** (if not installed):  
   - Go to **Extensions** (`Ctrl + Shift + X`).  
   - Search for **Live Server** and install it.  
4. **Start the game**:  
   - Right-click on `index.html`.  
   - Select **"Open with Live Server"**.  
5. The game will open in your browser and **automatically refresh** when you make changes.  

---

### ✅ **Method 3: Run on a Local HTTP Server** (For Advanced Users)  
#### **Using Python (Built-in HTTP Server)**  
1. Open the **project folder** in **Terminal / Command Prompt**.  
2. Run this command (**Python 3** required):  
   ```bash

   python -m http.server 8000

🔧 Future Improvements
✅ Add Single Player Mode (with AI opponent)
✅ Add Leaderboard and Score Tracking
✅ Improve UI animations
✅ Add Sound Effects for better game feedback
