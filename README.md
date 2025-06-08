

# 🎮 Tic Tac Toe Game – Python Project

This project is a classic implementation of the **Tic Tac Toe (X-O)** game using **Python**. It allows two players to play against each other in a turn-based CLI (Command-Line Interface) environment.

---

## 📌 Table of Contents
- [About the Game](#about-the-game)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Features](#features)
- [How to Run](#how-to-run)
- [Sample Output](#sample-output)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Author](#author)

---

## 🕹️ About the Game

Tic Tac Toe is a two-player strategy game played on a 3×3 grid. Players take turns placing their marks (`X` and `O`) in empty squares. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

This project helps understand:
- Basic Python programming
- Control structures
- Function design
- Loops and conditionals
- Game logic

---

## 🛠 Technologies Used

- Python 3.x
- No external libraries – pure Python!

---

## 🔄 How It Works

- The game board is displayed using numbers 1-9.
- Player 1 uses `X` and Player 2 uses `O`.
- Players take turns choosing an available position.
- The game checks for:
  - Win conditions (3 in a row)
  - Draw condition (board full, no winner)

---

## 🌟 Features

- Simple and interactive command-line interface.
- Checks for invalid inputs (e.g., already occupied cells).
- Game ends with a winner or draw message.
- Replay option can be added easily.

---

## ▶️ How to Run

1. **Clone the repository**:
```bash
git clone https://github.com/pradeepsingh077/tic_tac_toe.projects.git
```
2. **Run the game**:
```bash
python tic_tac_toe.py
```

## Welcome to Tic Tac Toe!

 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

Player 1, choose your position (1-9): 5

 1 | 2 | 3
-----------
 4 | X | 6
-----------
 7 | 8 | 9

...

🎉 Player 1 wins! Congratulations!

# 🚀 Future Improvements
Add AI opponent using Minimax Algorithm

GUI version using Tkinter or Pygame

Add score tracking and replay functionality

Online multiplayer version (socket programming)

# 📄 License
This project is licensed under the MIT License.

# 👨‍💻 Author
Pradeep Singh
📍 Noida, India

