# Pygame File Runner with Alpha-Beta Pruning AI

I am SAI PRATHEEK REDDY .This project is a Pygame application that provides an interface to choose and run different Python scripts. The key feature is the AI algorithm implemented using Alpha-Beta Pruning for one of the game options.
## Features
- *Graphical User Interface*: Simple and intuitive menu interface using Pygame.
- *Alpha-Beta Pruning AI*: Advanced AI algorithm implemented for the "Play with AI" game option, offering efficient and competitive gameplay.
- *Script Execution*: Runs specified Python scripts based on user selection.
- *Error Handling*: Checks if the specified file exists before attempting to run it.
## Requirements
- Python 3.x
- Pygame library

You can install the required libraries using the following command:
sh
pip install pygame
## How to Run
1. Clone the repository:
sh
git clone https://github.com/yourusername/pygame-file-runner.git

2. Navigate to the project directory:
sh
cd pygame-file-runner

3. Ensure you have the required Python scripts (game1.py and game2.py) in the same directory or adjust the paths accordingly. The game2.py script should contain the Alpha-Beta Pruning AI implementation.
4. Run the main script:
sh
python main.py
## File Structure
pygame-file-runner/
│
├── main.py            # Main script with the Pygame menu
├── game1.py           # Script for the first game option (Play with a Friend)
├── game2.py           # Script for the second game option (Play with AI using Alpha-Beta Pruning)
└── README.md          # This README file

## Usage

- Launch the application and a window will appear with the menu.
- Press 1 to run game1.py (Play with a Friend).
- Press 2 to run game2.py (Play with AI using Alpha-Beta Pruning).
- Press 3 to exit the application.

## Alpha-Beta Pruning AI

The AI in game2.py utilizes the Alpha-Beta Pruning algorithm, which is an optimization of the minimax algorithm. This allows the AI to evaluate possible moves efficiently and make competitive decisions in the game, providing a challenging experience for players.
