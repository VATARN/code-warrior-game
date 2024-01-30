# Code Warrior: Platformer Game

## Overview

Code Warrior is an intermediate-level Object-Oriented Programming (OOP) project, showcasing a platformer game built using HTML, CSS, and JavaScript. This game challenges players to navigate a character through various platforms and checkpoints, using keyboard inputs for movement and interaction.

## Features

- **Interactive Start Screen:** Introduces the game with instructions and a start button.
- **Dynamic Gameplay:** Control a player character to navigate through platforms and reach checkpoints.
- **Keyboard Control:** Utilize arrow keys for movement and the spacebar for jumping.
- **Canvas-Based Rendering:** The game is rendered on an HTML5 canvas, providing smooth graphics and animations.
- **Checkpoint System:** Players aim to reach multiple checkpoints, with a congratulatory message upon reaching the last one.
- **Collision Detection:** Implemented for platforms and checkpoints, enhancing the gameplay experience.

## How to Play

1. **Starting the Game:** Click the 'Start Game' button on the initial screen.
2. **Movement:** Use the left and right arrow keys to move the player horizontally and the spacebar to jump.
3. **Objective:** Navigate through the platforms to reach the yellow checkpoints.
4. **Winning the Game:** Reach the final checkpoint to complete the game.

## Technical Implementation

### Classes and Objects

- **Player Class:** Manages the player character's properties and behaviors, such as position, velocity, and drawing on the canvas.
- **Platform Class:** Represents individual platforms in the game with their properties and rendering logic.
- **Checkpoint Class:** Defines the checkpoints with their properties and claim method when reached by the player.

### Game Logic

- **Animation Loop:** The `animate` function is the heart of the game loop, updating and rendering the game frame by frame.
- **Collision Detection:** Implemented to handle interactions between the player, platforms, and checkpoints.
- **Keyboard Event Listeners:** Detects and processes user input for controlling the player character.

### Styling and Layout

- The game's appearance and layout are styled using CSS, with a focus on a user-friendly and engaging interface.

## Running the Game

To play the game, open the HTML file in a web browser. No additional setup is required. Ensure your browser is up-to-date for the best experience.

## Contributing

Contributions to enhance the game, such as adding new levels, improving the UI, or refining the game mechanics, are welcome. Feel free to fork the repository, make your changes, and submit a pull request.
