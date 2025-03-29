# SpaceInvadersGame
Project Title: Space Invaders Game Using Pygame

Project Description: This project is a simple Space Invaders game developed using Pygame, inspired by a tutorial from the FreeCodeCamp YouTube channel. This is not my original project but was undertaken purely for the learning process and to explore game development with Pygame. The game features a spaceship controlled by the player, enemies that move across the screen, bullets that can be fired to eliminate enemies, and a scoring system.

Project Features:
Player Control: The player controls a spaceship using the left and right arrow keys.
Enemy Movement: Multiple enemies move horizontally and descend upon hitting screen boundaries.
Bullet Firing Mechanism: The player can fire bullets using the spacebar, and bullets move upward.
Collision Detection: The game checks for bullet-enemy collisions to update the score and reset enemies.
Game Over Mechanism: If an enemy collides with the player's ship, the game ends.
Background Music and Sound Effects: Continuous background music and sound effects for shooting and explosions.
Score Display: The player’s score is displayed at the top of the screen.

Code Explanation:
The Pygame library is used to handle game mechanics like rendering, event handling, and audio.
The mixer module from Pygame plays background music and sound effects.
Random module generates random enemy positions to make gameplay dynamic.
Math module is used for collision detection by calculating the distance between objects.
The game runs inside an infinite loop, updating player and enemy positions continuously.
Event handling allows movement control and bullet firing.
A game-over check stops enemy movement and displays the game-over message upon collision with the player.

This project served as an insightful introduction to game development concepts, such as event handling, collision detection, and sprite movement, using Python’s Pygame library.

For the characters that i have used in this game like-aliens,arcade space,spaceship etc. are taken from this website which offers you multiple icons that can be inserted into your works of your choice.-https://www.flaticon.com/

I have also inserted the same firing,explosion sound and background music which was shown in the tutorial video.
