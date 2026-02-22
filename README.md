# Tic-Tac-Toe

A two-player tic-tac-toe game that runs in the terminal, written in C++.

## How It Works

- Players take turns choosing a position (0-8) and entering X or O
- The board is displayed after each move
- The game checks for a winner after every turn and announces the result
- If all 9 spaces are filled with no winner, it's a draw

## Board Layout

```
 0 | 1 | 2
-----------
 3 | 4 | 5
-----------
 6 | 7 | 8
```

## Build and Run

```bash
g++ ttt.cpp ttt_functions.cpp -o tictactoe
./tictactoe
```

## File Structure

| File | Description |
|------|-------------|
| `ttt.cpp` | Main game loop |
| `ttt_functions.cpp` | Board display, input handling, and win detection |
| `ttt_functions.h` | Function declarations |
