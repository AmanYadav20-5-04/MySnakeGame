# 🐍 Python Snake Game 🎮

A classic arcade-style Snake game built entirely with Python's `turtle` graphics module. Guide your snake to eat food, grow longer, and aim for the highest score, all while avoiding walls and your own tail!

## ✨ Features

* **Classic Gameplay:** Enjoy the traditional Snake game mechanics.
* **Smooth Animation:** Uses `screen.tracer(0)` for fluid snake movement.
* **Score Tracking:** Keeps track of your current score during gameplay.
* **High Score Persistence:** Automatically saves and loads the highest score achieved to/from a `high_score.txt` file, even after closing the game.
* **Collision Detection:** Detects collisions with screen boundaries and the snake's own body.
* **Responsive Controls:** Navigate the snake using the `Up`, `Down`, `Left`, and `Right` arrow keys.
* **Game Over Delay:** A brief 1.5-second pause after game over before restarting, giving players time to react.

## 🚀 How to Run

1.  **Prerequisites:** Ensure you have Python 3 installed on your system.
2.  **Clone the Repository:**
    ```bash
    git clone https://github.com/AmanYadav20-5-04/MySnakeGame.git
    ```
3.  **Navigate to Project Directory:**
    ```bash
    cd Python-Snake-Game
    ```
4.  **Run the Game:**
    ```bash
    python main.py
    ```

## 🛠️ Project Structure

* `main.py`: The main game loop, screen setup, and collision detection.
* `snake.py`: Defines the `Snake` class, handling its segments, movement, and growth.
* `food.py`: Defines the `Food` class, managing its random placement.
* `scoreboard.py`: Manages the score and high score display, including file I/O for persistence.
* `high_score.txt`: A simple text file to store the high score (created/updated by the game).

## 💡 Future Enhancements (Ideas)

* **Difficulty Levels:** Implement options for different game speeds.
* **Sound Effects:** Add audio cues for eating food and game over.
* **Start/Game Over Screens:** More engaging introductory and end screens.
* **Obstacles:** Introduce static or dynamic obstacles on the playing field.

---
Enjoy playing the Snake Game!
By Aman Yadav 🫡
