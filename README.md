# Snake Game

A simple Snake game implemented in Python using the turtle library.

## Features 

- **Classic Snake gameplay** 
- **Simple graphics using the `turtle` library** 
- **Keyboard controls for movement**
- **Food spawning at random positions**
- **Collision detection**

## How to Play

- **Controls**: Use the arrow keys on your keyboard to navigate the snake.
- **Objective**: Guide the snake to eat the food that appears randomly on the screen. Each time the snake eats, it grows longer.
- **Game Over**: The game ends if the snake collides with the screen borders or with itself.

## Installation and Setup

1. **Prerequisites**:
   - Ensure you have Python installed on your system. You can download it from the [official Python website](https://www.python.org/).

2. **Clone the Repository**:
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```bash
     git clone https://github.com/andreary1/snake_game.git
     ```
   - Navigate to the project directory:
     ```bash
     cd snake_game
     ```

3. **Install Required Libraries**:
   - The game uses the `curses` library, which is standard in Unix-based systems but needs to be installed separately on Windows.
   - For Windows users:
     - Open PowerShell and run:
       ```bash
       python -m pip install windows-curses
       ```
     - Alternatively, you can run the provided `Curses_install.bat` file by double-clicking it, which will automatically install the necessary library.

4. **Running the Game**:
   - To start the game, run the `Snake.bat` file by double-clicking it.
   - If you encounter any issues, you can manually run the game by opening a terminal in the project directory and executing:
     ```bash
     python main.py
     ```
Enjoy the game!
