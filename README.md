Terminal Snake Game (Prototype)

This project is a prototype of a terminal-based snake-like game, written in C#. It provides basic functionality for a player that can move around the terminal window, collect items (foods), and change appearance based on interactions. However, the game is not yet fully playable and requires additional logic to complete the core gameplay loop.

Features
Implemented

Terminal Window Management

Detects and stores the size of the terminal window.

Player & Food Tracking

Tracks player and food positions dynamically.

Custom Appearances

Arrays states and foods store available player and food appearances.

Updates the player appearance when food is consumed.

Movement Handling

Supports directional movement based on user input.

Freeze Mechanic

Player movement can be temporarily frozen.

Game Initialization

Sets up the initial state when the game starts.

Missing Features

The following logic still needs to be implemented for a functional game:

Detect when the player consumes food.

Determine if the consumed food should freeze the player temporarily.

Handle special foods that increase player movement speed.

Logic to increase movement speed progressively.

Redisplay new food after the current one is consumed.

Proper input validation to terminate execution if unsupported keys are pressed.

Terminate execution if the terminal is resized during gameplay.# Nithin-A
