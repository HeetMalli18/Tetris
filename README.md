# Tetris Game

Welcome to the **Tetris Game**! This is a colorful console-based implementation of the classic Tetris game, where you can enjoy a visually appealing and interactive experience with different colored tetromino shapes.

## Features:
- **Colorful Tetriminos**: Each Tetrimino has a unique color, making the game visually appealing.
- **Board Customization**: Adjust the width and height of the game board for a more personalized experience.
- **Controls**: Easy-to-use controls for rotating and moving the pieces.
- **Pause/Resume**: You can pause the game anytime and resume when you're ready.
- **Score System**: Keep track of your score as you clear lines.
- **Game Over & Restart**: After losing, you can restart the game or quit.

## Gameplay Instructions:

### Controls:
- **Move Left**: `a`
- **Move Right**: `d`
- **Soft Drop (move down faster)**: `x`
- **Rotate Clockwise**: `w`
- **Rotate Counterclockwise**: `s`
- **Pause the Game**: `p`
- **Resume the Game**: `r`
- **Restart the Game**: `r` (when the game is over)
- **Quit the Game**: `q`

### Features:
- You start with a random tetromino piece.
- The piece will fall down automatically, and you can move it left, right, or rotate it to fit the board.
- When a row is completely filled, it is cleared, and you score points.
- The game ends when the tetromino pieces stack up to the top of the screen.

## Installation:

### Prerequisites:
- You need a **C++ compiler** (e.g., **G++**, **Visual Studio**) that supports C++11 or later.
- The game is designed for **Windows** due to the usage of the `windows.h` library for cursor control and color customization.

### Steps to Compile and Run:

1. **Download or clone the repository** to your local machine.
2. **Open the terminal/command prompt** and navigate to the folder where the file is saved.
3. **Compile the program** with your C++ compiler (make sure you have C++11 support or later):

   ```bash
   g++ -o tetris tetris.cpp
