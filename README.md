## Overview
This project is a simple interactive Pac-Man-like game created using HTML5 Canvas and JavaScript. The game allows the user to control a Pac-Man character using the arrow keys on the keyboard. The Pac-Man character moves in a 2D canvas, and its mouth opens and closes while moving, mimicking the iconic look of Pac-Man.

## Features
- **Pac-Man Animation**: The Pac-Man character is rendered using canvas drawing functions. Its mouth opens and closes in an animation loop.
- **Keyboard Control**: The user can control Pac-Man's movement using the arrow keys (left, right, up, down).
- **Canvas Drawing**: The game utilizes the HTML5 `<canvas>` element to render the game world and animate the character.

## How It Works
- **Canvas**: The game is displayed on an HTML `<canvas>` element with a specified width and height.
- **Movement**: The Pac-Man's position is updated at regular intervals (every 200ms), and the direction of movement is controlled by keyboard input.
- **Animation**: The Pac-Man character's mouth opens and closes in a cycle, depending on the `bite` state. The character's direction is updated based on user input and rotated accordingly.

## Controls
- **Arrow Keys**:
  - **Left Arrow**: Move Pac-Man left.
  - **Up Arrow**: Move Pac-Man up.
  - **Right Arrow**: Move Pac-Man right.
  - **Down Arrow**: Move Pac-Man down.

## Installation & Usage
1. Clone the repository or download the HTML file.
2. Open the HTML file in any modern web browser.
3. Use the arrow keys to control the Pac-Man character.

## Technologies Used
- **HTML5**: Structure and layout of the game.
- **JavaScript**: Game logic, animation, and event handling.
- **Canvas API**: Drawing the Pac-Man character and animating its movement.

## Customization
- You can adjust the canvas size by changing the `width` and `height` attributes of the `<canvas>` element.
- You can modify the movement speed by adjusting the `pcX` and `pcY` increment values in the `update` function.
- The Pac-Man color can be changed by modifying the `ctx.fillStyle` property within the `packman()` function.

## License
This project is open-source and can be freely used, modified, and distributed.

