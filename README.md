# Sudoku Game in C++

This is a console-based Sudoku game written in C++. The project features a randomly generated Sudoku puzzle with three levels of difficulty, interactive gameplay, and the ability to save and load your progress.
![image](https://github.com/user-attachments/assets/78b9ba9a-5ab8-4e7f-8822-a1043587d4de)
## Features

- 🎲 Random Sudoku board generation
- 📊 Three difficulty levels:
  - Easy
  - Medium
  - Hard
- 💾 Save and load your game
- 🎮 User-friendly terminal interface with colored output for better visibility
- ✅ Win detection logic

## How to Play

1. **Run the program**.
2. Choose an option from the main menu:
   - `1` to start a new game
   - `2` to load a saved game
   - `3` to exit
3. If starting a new game, select difficulty level (`1` for easy, `2` for medium, `3` for hard).
4. Enter the row and column of the cell you want to change, followed by the number you want to place.

## Build & Run

Make sure you have a C++ compiler installed (e.g., g++, clang++).

```bash
g++ -o sudoku sudoku.cpp
./sudoku
File Structure
sudoku.cpp – The main source code of the game.

file.txt – Used to store the game state for save/load functionality.

Example
pgsql
Copy
Edit
1 new game
2 load game
3 exit
> 1
> 2   ← selects Medium difficulty
Then, enter coordinates and a number, like:

markdown
Copy
Edit
> 3 4
> 7
Notes
Make sure file.txt is writable in your project directory.

Terminal must support ANSI escape sequences for colors to display correctly.

License
This project is released under the MIT License. Feel free to use, modify, and share!
