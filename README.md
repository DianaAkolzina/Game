# Game
Labyrinth Game
This is a 2D Labyrinth game implemented in Python using the Pygame and PIL libraries. The player must navigate through a series of mazes while avoiding walls, and collect prizes (hearts) to increase their score. The game consists of multiple levels, each with a different maze layout.

Dependencies
Pygame
Pillow (PIL)
Features

Multiple labyrinth levels with different layouts
Customizable labyrinth images
Character movement with smooth animation and collisions
Prize collection to increase score
Display current score on the screen
End game message after completing all levels


How to Run
Install the required dependencies:

pip install pygame
pip install pillow

Run the game by executing the Python script:

python game.py


Game Mechanics
The player moves using the arrow keys (up, down, left, right)
Colliding with a wall will reset the current level
Collecting a prize (heart) will increase the player's score and move to the next level
Completing all levels will display a congratulatory message and end the game

Code Structure
The code is organized into several classes:

Person: Represents the player character, handling movement, animation, and drawing
Labyrinth: Represents a labyrinth level, loading images, handling collisions, and drawing
Prise: Represents the prize (heart) object, handling position, collection, and drawing
gameLoop: Main game loop, managing game state, level transitions, and input handling

