# Tic-Tac-Toe
It's a childhood game in India we call this game as O-X game.
Tic Tac Toe
Project Description
It is a simple console-based Tic Tac Toe game for two players. The game alternates turns between Player 1 (X) and Player 2 (O) until a winner is determined or the board is full. Optional functionality includes saving the game state and resuming it later.

Features Implemented
Interactive game board: Displays the game's current state after every turn.

Turn-based gameplay: Alternates turns between two players.

Win and draw detection: Automatically determines if a player has won or if the game ends in a draw.

Input validation: Ensures players enter valid moves.

Save and resume: (Optional) Allows saving the game state to a file and resuming it later.

How to Run the Project
Clone this repository:

git clone https://github.com/yourusername/Tic-Tac-Toe.git
Navigate to the project directory:

cd Tic-Tac-Toe
Run the game:

python tic_tac_toe.py
Installation Instructions
Ensure you have Python 3.8+ installed on your system.

No additional libraries are required.

Gameplay Instructions
Start the game: The program asks if you want to load a saved game or start a new one.

Make moves: Players take turns entering numbers (1-9) corresponding to board positions:

 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9
Win or draw: The game ends when a player aligns three of their symbols (horizontally, vertically, or diagonally) or when all cells are filled (draw).

Save and resume: Players can save the game state at any time and resume later.

Example
Starting the Game
Do you want to load the last saved game? (yes/no): no
Current Board:
 - | - | -
---+---+---
 - | - | -
---+---+---
 - | - | -
Player 1 (X), it's your turn!
Enter your move (1-9): 5
Winning Scenario
Current Board:
 X | O | X
---+---+---
 O | X | -
---+---+---
 - | - | X
Player 1 (X) wins!
Saving the Game
Do you want to save the game? (yes/no): yes
Game saved successfully!
File Structure
tic_tac_toe.py: Main Python file containing the game logic.

game_state.txt: (Optional) Stores the saved game state, including the board and current player's turn.

Future Improvements
Add a single-player mode with AI.

Enhance the user interface with colors and better visuals.

Include a leaderboard to track wins and draws over multiple sessions.

License
This project is licensed under the MIT License.

