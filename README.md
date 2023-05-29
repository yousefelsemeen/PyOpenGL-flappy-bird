# Flappy Bird Clone

This is a clone of the popular Flappy Bird game implemented using OpenGL and GLUT in Python.
This project was for the AI subject in college with my team.

## Files

There are two files:

- `main.py`: Contains the main game loop and handles events. Initializes the game window.
- `classes.py`: Contains classes for the bird, pipes, and base. Handles drawing and motion.

## Images

<img src="https://i.ibb.co/dP3NTmc/ready.png" alt="Ready" height="500">
<img src="https://i.ibb.co/1mL8zbP/gameplay.png" alt="Gameplay" height="500">
<img src="https://i.ibb.co/QFZccbY/gameover.png" alt=" Over" height="500">

## Classes

- `Bird`: Represents the flapping bird. Has attributes for position, motion, textures, etc. Can flap wings, move, die, and reset.
- `Pipe`: Represents a single pipe obstacle. Has upper and lower pipe, gap size, position, motion, and texture. Can move and draw.
- `Base`: Represents the ground base. Has position, texture, and can move and draw.

## Controls

- Spacebar: Flap the bird's wings

## Objective

Navigate the bird through the gap in the pipes without hitting them. Flap to make the bird rise, fall through gravity to drop. Score increases by 1 for each pipe passed.

## Libraries Used

- OpenGL
- GLUT
- Random

## Running the Game

Run `python main.py` to start the game.
