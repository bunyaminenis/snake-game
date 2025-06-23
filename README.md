🐍 Snake Game – Python Turtle Edition
This is a recreation of the classic Snake game using Python’s built-in turtle module. The game features food spawning, score tracking, and high score persistence via a local text file. It’s a beginner-friendly project ideal for practicing Object-Oriented Programming (OOP) in Python.

🎮 Features
Snake movement using W, A, S, D keys

Food spawns randomly on screen

Score tracking and high score saving (data.txt)

Collision detection with walls and tail

Clean OOP structure (separate files for snake, food, scoreboard)

📁 Project Structure
📦 snake-game/
├── main.py          # Game engine and loop
├── snake.py         # Snake logic and controls
├── food.py          # Food spawning logic
├── scoreboard.py    # Score display and high score management
├── data.txt         # Stores the highest score locally

▶️ How to Run
Make sure you have Python 3.x installed. Then:
git clone https://github.com/yourusername/snake-game.git
cd snake-game
python main.py
Use:

W = up

S = down

A = left

D = right

📌 Requirements
Python 3.x

No external libraries are required – uses the built-in turtle module

🛠️ Implementation Details
snake.py: Manages the creation, movement, growth, and reset of the snake using Turtle segments.

food.py: Spawns food at random screen coordinates and resets after being eaten.

scoreboard.py: Displays and updates the score and high score.

main.py: Sets up the screen and runs the game loop with real-time collision detection and input listening.
