# Tic-Tac-Toe
This is a simple web-based Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to take turns marking "X" and "O" on a 3x3 grid until one player wins or the game ends in a draw.


## Features
- **Two-player mode:** Players alternate turns to play the game.
- **Winning condition detection:** The game detects and announces the winner if a player manages to get three in a row (horizontally, vertically, or diagonally).
- **Draw condition:** If the grid is completely filled without a winner, the game ends in a draw.
- **Reset button:** Allows players to reset the board and start a new game after finishing the current one.


## Technologies Used
- **HTML5:** To structure the game layout.
- **CSS3:** For styling the game board and visual elements.
- **JavaScript (ES6):** For handling game logic and player interaction.


## How It Works
### Game Logic
- The game board is represented as a 3x3 grid in HTML. Each cell is clickable and tied to a JavaScript event listener.
- JavaScript keeps track of the current player and switches between "X" and "O" after every valid move.
- After every move, the game checks for winning conditions by comparing the state of the board (horizontal, vertical, and diagonal lines).
- If a player wins or if the game ends in a draw, the appropriate message is displayed, and no more moves can be made until the board is reset.

### Winning and Draw Conditions
- A player wins if they manage to get th
- ree of their marks in a row, either horizontally, vertically, or diagonally.
- If all the grid cells are filled and no player has won, the game ends in a draw.

### Restart Functionality
- After a game is finished, players can click the "Restart" button to clear the board and start a new game without refreshing the page.

## Screenshot
![image](https://github.com/user-attachments/assets/4cb6a12c-6437-422b-ae82-b251677cad35)


