11:25 AMClaude responded: White move (E2 E4, Q to quit, U to undo, R to redo):markdown<h1 align="center">♟️ Terminal Chess Game</h1>
<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Course-Introduction%20to%20Computing-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IDE-Visual%20Studio-purple?style=for-the-badge&logo=visualstudio&logoColor=white"/>
</p>

---

## 📌 Overview

A fully playable **2-player console Chess Game** built in C++.
Features complete move validation, check and checkmate detection,
and undo/redo functionality — all without any external libraries.

---

## ⚙️ Features

| Feature | Description |
|---------|-------------|
| ♟️ Full Chess Board | 8x8 board displayed in terminal |
| ✅ Move Validation | Legal moves for all 6 piece types |
| 👑 Check Detection | Warns when king is in check |
| 🏁 Checkmate Detection | Ends game when no escape moves exist |
| ↩️ Undo | Undo last move anytime |
| ↪️ Redo | Redo undone move |
| 🚪 Quit | Player can resign anytime |
| 🔒 Self-Check Prevention | Illegal moves that expose king are blocked |

---

## 🧠 Concepts Used

![Arrays](https://img.shields.io/badge/Arrays-blueviolet?style=for-the-badge)
![Functions](https://img.shields.io/badge/Functions-orange?style=for-the-badge)
![Loops](https://img.shields.io/badge/Loops-blue?style=for-the-badge)
![Conditionals](https://img.shields.io/badge/Conditionals-red?style=for-the-badge)
![Char Arrays](https://img.shields.io/badge/Char%20Arrays-success?style=for-the-badge)
![Game Logic](https://img.shields.io/badge/Game%20Logic-yellow?style=for-the-badge)

---

## ♟️ Pieces & Symbols

| Piece | White | Black |
|-------|-------|-------|
| King | K | k |
| Queen | Q | q |
| Rook | R | r |
| Bishop | B | b |
| Knight | N | n |
| Pawn | P | p |

---

## 🎮 How to Play

```
White move (E2 E4, Q to quit, U to undo, R to redo):
```

- Enter **source** and **destination** squares
- Example: `E2 E4` moves piece from E2 to E4
- Type `U` to undo last move
- Type `R` to redo undone move
- Type `Q` to quit/resign

---

## 📤 Sample Output

```
    A   B   C   D   E   F   G   H
  +---+---+---+---+---+---+---+---+
8 | r | n | b | q | k | b | n | r |
  +---+---+---+---+---+---+---+---+
7 | p | p | p | p | p | p | p | p |
  +---+---+---+---+---+---+---+---+
6 | . | . | . | . | . | . | . | . |
  +---+---+---+---+---+---+---+---+
...
White move (E2 E4, Q to quit, U to undo, R to redo):
```

---

## ▶️ How to Run

### 🖥️ Visual Studio
1. Create new **Empty Project** → C++
2. Add `main.cpp` to project
3. Press **Ctrl + F5** to Run
4. Type `Y` to start the game

### 💻 VS Code
```bash
g++ main.cpp -o chess
./chess
```

### 🖱️ Dev C++
1. Open `main.cpp`
2. Press **F11** to Compile & Run

---

## 📁 Project Files

```
terminal-chess-cpp/
├── main.cpp        → complete chess game source code
└── README.md       → project documentation
```

---

## ⚠️ Important Notes

- 2 player game — no AI opponent
- No external libraries used
- Pure C++ with arrays and functions only
- Undo/Redo history stores up to 1000 moves

---

## 👩‍💻 Author

**Aqsa Ismail** | [GitHub](https://github.com/aqsaismail04) | [LinkedIn](https://www.linkedin.com/in/aqsaismail04/)
