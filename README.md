# codsoft-C++-task-3


# program Explanation:

This C++ program implements a simple console-based version of the classic Tic Tac Toe game. The game allows two players to take turns marking 'X' and 'O' on a 3x3 grid. The program includes functions for printing the board, checking for a winner, checking for a tie, and handling player moves. The game loop continues until the players decide not to play again.

# Key Features:

1. **Player Turns:** Players alternate turns, with 'X' and 'O' marking the board.

2. **Random Starting Player:** The starting player is randomly selected at the beginning of each game.

3. **Winning Conditions:** The game checks for a winner after each move, considering rows, columns, and diagonals.

4. **Tie Condition:** If the board is full and no winner is found, the game ends in a tie.

5. **Play Again Option:** After each game, players have the option to play again.


# Tic Tac Toe

Welcome to the Tic Tac Toe game implemented in C++! This program allows two players to play the classic game of Tic Tac Toe on a 3x3 grid.

# How to Play

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/your-username/tic-tac-toe.git
    ```

2. Compile the program using a C++ compiler (e.g., g++).

    ```bash
    g++ tic_tac_toe.cpp -o tic_tac_toe
    ```

3. Run the compiled executable.

    ```bash
    ./tic_tac_toe
    ```

4. Follow the on-screen prompts to make moves in the Tic Tac Toe game.

# Features

- Two players take turns making moves ('X' and 'O').
- Random selection of the starting player.
- The game ends when a player wins or it's a tie.
- Option to play again after a game ends.

# Gameplay

- Players input their moves by entering a number from 1 to 9 to represent the position on the board.
- The board is displayed after each move.
- The game checks for a winner or a tie after each move.

# Implementation Details

- 2D vector represents the Tic Tac Toe board.
- Functions handle printing the board, checking for a winner, checking for a full board, and handling player moves.
- The game loop continues until the players decide not to play again.

# Example Gameplay

Welcome to Tic Tac Toe!
---------------------START THE GAME--------------------------
 1 | 2 | 3 |
 ---------
 4 | 5 | 6 |
 ---------
 7 | 8 | 9 |
Player X, enter your move in game (1-9): 5
 1 | 2 | 3 |
 ---------
 4 | X | 6 |
 ---------
 7 | 8 | 9 |
...
Player X wins! Congratulations, you win!
Do you want to play again? (yes/no): no
Thanks for playing Tic Tac Toe!................

# sample image

![c to1](https://github.com/Srivarthaniselvam/codsoft-C-task-3/assets/151417502/25857af5-a444-4383-9a7e-2b8518227a2f)
![c to2](https://github.com/Srivarthaniselvam/codsoft-C-task-3/assets/151417502/f2290492-b730-49e7-bfee-62a1bce5d51f)
![c to3](https://github.com/Srivarthaniselvam/codsoft-C-task-3/assets/151417502/def69ac6-7f2e-4cd5-a630-d83b8b285703)
![c to4](https://github.com/Srivarthaniselvam/codsoft-C-task-3/assets/151417502/2c731b8f-c2c0-41fe-b0b2-f6ef2959c808)
![c to51](https://github.com/Srivarthaniselvam/codsoft-C-task-3/assets/151417502/c79e5f23-70b2-46fa-8645-a3ae0298a754)
![c to6](https://github.com/Srivarthaniselvam/codsoft-C-task-3/assets/151417502/05e92bf6-c89c-4f39-b8a7-15f8531118a4)

