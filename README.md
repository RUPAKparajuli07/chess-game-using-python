## Two-Player Pygame Chess - Documentation

### Overview:

This Pygame script implements a two-player chess game with a graphical user interface. The game follows the standard rules of chess, allowing players to make moves using the graphical representation of chess pieces on an 8x8 board.

### Constants:

- `WIDTH` and `HEIGHT`: Define the dimensions of the Pygame window.
- `screen`: Represents the Pygame display surface.
- `font`, `medium_font`, `big_font`: Pygame font objects for rendering text at different sizes.
- `timer`: Pygame clock object for controlling the frame rate.
- `fps`: Sets the frames per second for the game.
- Piece-related constants such as `white_pieces`, `black_queen`, etc.

### Functions:

#### Drawing Functions:

- `draw_board`: Draws the main chessboard, player status, and buttons on the Pygame window.
- `draw_pieces`: Draws the chess pieces on the board based on their current positions.
- `draw_captured`: Draws captured pieces on the side of the Pygame window.
- `draw_check`: Draws a flashing square around the king if it is in check.
- `draw_game_over`: Draws the game over screen with the winner's information.

#### Move Validation Functions:

- `check_options`: Checks all possible moves for each piece on the board.
- `check_king`, `check_queen`, `check_bishop`, `check_rook`, `check_pawn`, `check_knight`: Determine valid moves for specific types of chess pieces.
- `check_valid_moves`: Retrieves valid moves for the currently selected piece.

#### User Interaction:

- Handling mouse clicks and keyboard events to facilitate player interactions.
  
### Usage:

1. **Game Initialization:**
   - Instantiate the Pygame window.
   - Load initial game state, including piece positions.

2. **Game Loop:**
   - Continuously update the screen based on player interactions.
   - Allow players to select and move pieces.

3. **Move Validation:**
   - Check the validity of moves based on chess rules.
   - Highlight valid moves for the selected piece.

4. **End of Game:**
   - Determine a winner based on the game outcome.
   - Display a game-over screen with the option to restart.

### Customization:

- Developers can customize the game by modifying piece images, initial positions, and other graphical elements.
- Explore and extend the code to implement additional features or variations of chess.

### Note:

This documentation provides an overview of the key constants and functions in the script, enabling developers to understand, modify, and customize the Two-Player Pygame Chess game.
