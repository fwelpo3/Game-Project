Mario
A Pygame project that allows the player to control Mario and move him around the screen. The player can also move stones by pushing them.

Requirements
Pygame
Running the game
To run the game, clone the repository and run the following command in your terminal:

Copy code
python main.py
Controls
Use the arrow keys to move Mario up, down, left, and right.
Use the D key to push stones to the right.
Project structure
Bilder: This folder contains all the images used in the game, including the backgrounds, Mario running and stones.
main.py: This is the main script that runs the game. It initializes Pygame, loads the images, and contains the main game loop.
move_stone: This function takes in the x and y coordinates of the stone and the player's rectangle, and moves the stone based on the player's movements.
line: This function draws a line on the screen.
plyer_image: This list contains the images of Mario running.
o_background: This is the original background image.
background: This is the background image scaled to fit the screen.
plyer: This is the image of Mario.
plyer_rect: This is the rectangle object for Mario's image.
speed: This is the speed at which Mario and the stone move.
clock: This is a Pygame clock object that controls the frame rate of the game.
