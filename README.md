# 🎮 AI-Based Tic-Tac-Toe (Minimax Algorithm)

A console-based **Tic-Tac-Toe** game implemented in **C++** where the user plays against an AI bot. The bot uses the **Minimax Algorithm** from Game Theory to always choose the optimal move, making it impossible to defeat.

---

## 📌 Features

- 🤖 AI opponent powered by the **Minimax Algorithm**
- 👤 Single-player gameplay
- 🎯 Optimal move selection
- 🖥️ Simple console interface
- 📍 Displays board coordinates for easy move selection
- ⚡ Lightweight and easy to run

---

## 🛠️ Technologies Used

- **Language:** C++
- **Concepts:**
  - Minimax Algorithm
  - Game Theory
  - Recursion
  - Backtracking
  - 2D Arrays

---

## 📂 Project Structure

```
.
├── main.cpp        # Source code
└── README.md       # Project documentation
```

---

## ▶️ How to Run

### Compile

Using g++:

```bash
g++ main.cpp -o tic_tac_toe
```

### Run

```bash
./tic_tac_toe
```

For Windows:

```bash
g++ main.cpp -o tic_tac_toe.exe
tic_tac_toe.exe
```

---

## 🎮 Gameplay

1. Enter your name.
2. The **first letter** of your name is used as your game symbol.
3. The AI always plays as **X**.
4. You always make the first move.
5. Enter your move using row and column numbers.

Example:

```
Player Move:
1 2
```

which means

```
Row = 1
Column = 2
```

---

## 🖥️ Board Layout

```
_ _ _
_ _ _
_ _ _

Controllers

(1,1) (1,2) (1,3)
(2,1) (2,2) (2,3)
(3,1) (3,2) (3,3)
```

---

## 🧠 AI Strategy

The AI uses the **Minimax Algorithm**, a decision-making algorithm from Game Theory.

- Maximizes its own chances of winning.
- Minimizes the opponent's chances.
- Explores every possible game state recursively.
- Always selects the optimal move.

Because Tic-Tac-Toe has a relatively small search space, the AI evaluates every possible move before making a decision.

---

## ⚙️ Algorithm Overview

```
Player Move
      │
      ▼
AI generates all possible moves
      │
      ▼
Apply Minimax recursively
      │
      ▼
Evaluate board states
      │
      ▼
Choose move with highest score
```

Scoring:

| Result | Score |
|---------|------:|
| AI Wins | +100 |
| Player Wins | -100 |
| Draw | 0 |

---

## 📸 Sample Output

```
ENTER YOUR NAME :
Hamid

FIRST LETTER OF YOUR NAME DENOTES YOUR PLAYER

X DENOTES SYSTEM PLAYER

FIRST TURN IS YOURS

BOARD

_ _ _
_ _ _
_ _ _

Hamid's Move:
2 2

Bot's Move:
1 1

X _ _
_ H _
_ _ _
```

---

## 🚀 Future Improvements

- Alpha-Beta Pruning for faster search
- Difficulty levels (Easy, Medium, Hard)
- Better input validation
- Graphical User Interface (GUI)
- Score tracking
- Multiplayer mode
- Undo/Redo feature

---

## 📚 Concepts Demonstrated

- Minimax Algorithm
- Game Theory
- Recursive Search
- Backtracking
- Decision Trees
- C++ Programming
- Console Application Development

---
## 👨‍💻 Author

**Md. Hamid**

GitHub: https://github.com/mdhamid28

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
