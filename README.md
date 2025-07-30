# Jungle Relic Quest - A Multi-Level Pygame Adventure

Jungle Relic Quest is an interactive adventure game built with Python and the Pygame library. The player navigates through three distinct levels, each with unique challenges, obstacles, and objectives. This project showcases modular code design, event handling, and complex game logic.

**[Click here to see a gameplay screenshot!]** <-- *Replace this with a real screenshot of your game!*

## Technologies Used
* **Language:** Python
* **Library:** Pygame
* **Development Tools:** PyCharm

## Key Features
* **Three Unique Levels:** The game is structured with three separate level modules, each presenting a different gameplay style:
    1.  **Level 1:** A jungle maze requiring precise movement to avoid walls and traps.
    2.  **Level 2:** A river rapids escape with moving hazards and progressively increasing difficulty.
    3.  **Level 3:** A timed temple puzzle involving interactive levers and patrolling guardians.
* **Pixel-Perfect Collision:** Implemented precise collision detection using masks to ensure fair and accurate interactions between the player and hazards.
* **Dynamic Game Objects:** Features moving enemies, interactive objects, and dynamic UI elements that update in real-time.
* **State Management:** A central game loop manages the progression between levels and handles win/loss conditions, triggering different display screens.

## How to Run
1.  Ensure you have Python and Pygame installed (`pip install pygame`).
2.  Clone this repository.
3.  Place all image assets in the same directory as the `.py` files.
4.  Run the main game file: `python game.py`
