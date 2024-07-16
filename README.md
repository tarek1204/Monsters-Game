# Monsters-Game
### Description: Simple Monsters Game

This Java project, inspired by Derek Banas' tutorial, implements a basic console-based game where monsters move on a 10x10 grid. Each monster has attributes such as health, attack power, and movement capabilities. Here’s a breakdown of its components:

- **Monster Class**: Represents individual monsters on the game board. Each monster has attributes like health, attack power, and movement. They can move randomly across the grid and interact with other monsters.
  
- **Battle Board**: A 10x10 grid where monsters move. It uses ASCII characters to represent different states (e.g., '*' for empty space, individual characters for monsters).

- **Game Logic**:
  - **Build Battle Board**: Initializes the game board with '*' characters.
  - **Redraw Board**: Prints the current state of the battle board.
  - **Movement**: Monsters move randomly in four directions (up, down, left, right) based on their movement capability. They avoid collisions with other monsters.
  - **Interaction**: Monsters can potentially encounter each other on the same grid cell, influencing future moves or interactions (not fully implemented here).

- **MonstersGame Class**: Contains the main method to orchestrate the game:
  - Initializes the battle board.
  - Creates an array of Monster objects with different attributes.
  - Moves each monster sequentially and updates the battle board after each move.

#### Features:
- **Dynamic Movement**: Monsters move randomly within the bounds of the grid, interacting based on their positions.
  
- **Console-based UI**: Utilizes ASCII characters for representing monsters and empty spaces on the grid.

- **Object-Oriented Design**: Encapsulates each monster’s state and behavior within the Monster class, facilitating easy extension and modification.

#### Potential Enhancements:
- **Combat Mechanics**: Implement combat between monsters when they occupy the same space.
  
- **User Interaction**: Extend the game with user input for controlling monsters or providing game commands.

- **Graphics**: Enhance the visual representation beyond ASCII characters for a more immersive experience.

This project serves as a foundational example for building more complex games or simulations involving grid-based movement and interaction among entities.
