# Tic-Tac-Toe

Just a simple 2-player console Tic-Tac-Toe game written in C++. I built this as a side project to mess around with grid rendering, basic game logic, and input handling.

By **DevChips**.

---

## Features

- **2-player local mode**: Player 1 is X, Player 2 is O.
- **Custom grid**: Draws a neat $3 \times 3$ ASCII grid with labeled X and Y axes.
- **Input checks**: Stops you from typing out-of-bound coords, picking taken spots, or crashing the app with bad inputs.
- **Win highlighting**: Replaces the winning 3-in-a-row path with `-` symbols when someone wins.
- **Draw detection**: Spots when the board is full and calls a tie.

---

## How to Build & Run

### Using Code::Blocks
Just open `TicTacToe.cbp` in Code::Blocks, hit **Build and Run** (`F9`).

### Using Command Line (g++)

```bash
# Compile
g++ main.cpp -o TicTacToe

# Run (Windows)
TicTacToe.exe

# Run (Linux / Mac)
./TicTacToe
```

---

## How to Play

1. Start the game and press `Enter`.
2. Enter your move by typing the coordinates as two numbers separated by a space (`X Y`):
   ```text
   Enter coordinates (X,Y) where you want to put symbol X:
   0 1
   ```
3. The top horizontal axis is **X**, and the vertical left axis is **Y**.
4. Get 3 in a row horizontally, vertically, or diagonally to win.

---

## Files

```text
.
├── main.cpp         # Main code
├── TicTacToe.cbp    # Code::Blocks project file
├── .gitignore       # Ignores build files / binaries
└── README.md        # This file
```

---

## License

Free to use, tweak, or copy whatever you want.
