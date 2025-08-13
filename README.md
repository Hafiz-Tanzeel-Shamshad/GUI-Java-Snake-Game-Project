# GUI Java Snake Game Project

![Language](https://img.shields.io/badge/Language-Java-orange)
![Type](https://img.shields.io/badge/Game-GUI-green)
![IDE](https://img.shields.io/badge/IDE-NetBeans-blue)

---

## Description
This project is a **Snake Game** implemented in **Java** using a **Graphical User Interface (GUI)**. It covers **basic to advanced Java concepts** and demonstrates the use of **Object-Oriented Programming (OOP)** principles such as **classes, objects, inheritance, and abstraction**.  

The motivation behind this project was to revisit a classic childhood game and use it as a practical exercise to strengthen Java programming skills.

---

## Introduction / Abstract
The game allows players to control a snake that moves around a bordered plane, eating food items (apples) to grow longer. The game ends if the snake hits itself or the boundaries of the screen. The main objective is to **maximize the length of the snake** while avoiding collisions.  

---

## Problem Identification
- The game is designed to **entertain users** while being **user-friendly**, suitable even for children.  
- Snake Game is a classic arcade game where the player aims to **catch as many fruits as possible** without colliding with the snake’s own body.  

---

## Gameplay Description
- **Controls:** Arrow keys (`Up`, `Down`, `Left`, `Right`) to move the snake.  
- **Objective:** Eat apples to grow longer. Avoid hitting your own tail.  
- **Scoring:** Each apple eaten increases the score and the snake’s length.  
- **Game Over:** Happens when the snake collides with itself. Press **Spacebar** to restart.

---

## System Features
- Graphical interface for **easy interaction**.  
- Snake grows longer with each apple eaten, increasing difficulty.  
- High score tracking.  
- Simple and intuitive gameplay suitable for all ages.  

---

## Inputs
- Arrow keys to control the snake's movement:
  - `Up` → North  
  - `Down` → South  
  - `Left` → West  
  - `Right` → East  

---

## Outputs
- Visual display of the snake and apples on the GUI.  
- Updates to **snake length** and **score** dynamically.  
- Game over message and option to restart.  

---

## Design Phase
- GUI-based design to improve user experience.  
- Program opens a window on launch, and gameplay starts with any arrow key.  

---

## Coding Phase
- Implemented using **OOP concepts**:
  1. Creating the game screen.  
  2. Building the snake.  
  3. Handling snake movement.  
  4. Detecting collisions (Game Over).  
  5. Placing food items randomly.  
  6. Growing the snake after eating food.  
  7. Displaying score and snake length.  

---

## Testing Phase
- **Directional Movement:** Tested all four directions (Up, Down, Left, Right).  
- **Collision Detection:** Snake cannot reverse into itself; must first turn orthogonally.  
- **Apple Collection:** Apples appear in random locations; eating increases snake length and score.  

---

## Note
- Snake starts moving in the **right direction** by default.  

---

## Conclusion
The Snake Game runs successfully with **no errors** and demonstrates the application of **Java OOP concepts** in a GUI-based game.  

---

## Future Directions
- Add **working buttons** and menus.  
- Improve game mechanics and collision limitations.  
- Introduce **levels, obstacles, and enhanced graphics** in future updates.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/GUI-Java-SnakeGame-Project.git
   ```
2. Open the project in **NetBeans IDE**.  
3. Run the **main class** to start the game.  
4. Use **arrow keys** to play and **Spacebar** to restart after game over.

## License

This project is **free to use and modify for educational purposes**.
