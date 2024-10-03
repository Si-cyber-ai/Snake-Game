Snake Game
This is a simple Snake Game implemented using Python's Turtle graphics module. The objective of the game is to control the snake to eat food while avoiding collisions with the walls or its own body. As the snake eats food, it grows longer and the game speed increases.

Features
Snake Movement: Control the snake using the keyboard (W, A, S, D keys).
Randomized Food: The food changes shape and color each time it's eaten.
Growing Snake: The snake grows longer as it eats food.
Score Tracking: The game keeps track of your current score and high score.
Game Over on Collision: The game resets if the snake collides with the wall or its own body.

Controls
W: Move up
S: Move down
A: Move left
D: Move right

Game Rules
The snake moves in the direction of the player's input and can eat the food that randomly appears on the screen.
Every time the snake eats food, it grows in length, the score increases by 10, and the game speeds up slightly.
The game ends if the snake collides with the wall or its own body.
Upon game over, the snake resets, and the high score is retained.

Installation and Running the Game
Ensure you have Python installed (Python 3.x recommended).
Install the Turtle module (comes pre-installed with Python).
Run the Python file using your preferred Python IDE or by executing the command:
python snake_game.py

Customization
Food Shapes/Colors: You can easily add more shapes or colors for the food by modifying the random.choice() calls for shape and color.
Snake Speed: The snake's speed increases gradually as you eat food. You can adjust the initial speed or the rate at which it increases by modifying the delay variable.

Future Enhancements
Add levels to increase difficulty over time.
Introduce obstacles or special food types with unique effects.
Add sound effects and background music.

Credits
Developed by Sidharth P Nair

Enjoy playing the game!
