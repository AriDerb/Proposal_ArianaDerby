# Title
Conquer the Cosmos!

## Repository
<https://github.com/AriDerb/Proposal_ArianaDerby.git>

## Description
For my final project, I want to create a 2D fixed shooter game inspired by Space Invaders using the Pygame library. The game will have a controllable character, a dog named Cosmo, that will move only horizontally across the screen to shoot incoming obstacles and collect special items for points.

## Features
- Player Movement
  - The left and right arrow keys will move the character horizontally across the screen. I plan to use Pygame's keyboard input functions to detect which keys are being pressed and update the character's position.

- Shooting Mechanic
  - The spacebar will shoot projectiles and destroy obstacles. I plan to create projectiles that spawn at the player's current position and move upward by updating their coordinates.

- Obstacles 
  - Asteroids will randomly spawn along the horizontal axis and move toward the bottom of the screen. I plan to use Python's random module to determine their starting positions and update their vertical coordinates during the game loop.

- Collectibles
  - Special items will also spawn randomly throughout the game and the player will gain points from touching them. I need to implement some detection to determine when Cosmo touches a collectible and increase the player's score accordingly.

- Collisions
  - I plan to implement Pygame's collision detection functions to check when projectiles hit obstacles, when Cosmo collects objects, or when obstacles hit Cosmo.

-Health
  - The player will start the game with a set number of lives. This number will be assigned to a variable that decreases when Cosmo collides with an obstacle.

-Keeping Score
  - The player's score will be assigned to a variable that increases when obstacles are destroyed or when special items are collected. I plan to display the score on the screen using Pygame's font functions.

-Difficulty
  - The difficulty will increase as obstacles gradually move faster the longer the player is alive. I plan on using a timer to determine when to increase the asteroids' speed.

-Display Final Score
  - I will use a conditional statement to check the player's lives. When the player's lives equal zero, the game will end, and the final score will be displayed.

## Challenges
- I need to search for any Pygame collision detection methods and learn how to implement them in my game.

- I will learn how to randomly generate multiple obstacles and collectibles, as well as manage all of these objects.

- I will learn how to gradually increase game difficulty and keep track of health.

- I will also learn how to incorporate original artwork into my game.

## Outcomes
Ideal Outcome:
- My ideal outcome is a fully functional arcade-style game featuring player movement, shooting, obstacles, collectibles, a scoring system, and increasing difficulty. I also hope to incorporate original artwork to create a visually appealing experience.

Minimal Viable Outcome:
- At minimum, I hope to create a playable game where the player can move left and right, shoot incoming obstacles, and earn points. I hope to at least have basic collision detection and a functional game-over condition.

## Milestones
- Week 1 (Nov. 8-14)
  1. Create initial game window and implement horizontal player movement
  2. Implement basic shooting mechanic

- Week 2 (Nov. 15-21)
  1. Create randomly spawning obstacles and collectibles
  2. Add collision detection for all game entities
  3. Create the basic scoring system

- Week 3 (Nov. 22-28)
  1. Implement health system and game-over screen
  2. Add speed up/gradually increasing difficulty 
  3. Start adding my original artwork 

- Week 4 (Nov. 29- Dec. 6)
  1. Finish visual elements
  2. Test gameplay and bug fixes
  3. Polish and prepare for submission

DUE DECEMBER 6
