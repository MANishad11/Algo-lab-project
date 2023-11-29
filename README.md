# Algo-lab-project
Name: Mustak Ahmed Nishad
Id: 222-115-118
****************************************************************************
### 1. Project Description:

This C++ code implements a simple console-based Tic-Tac-Toe game for two players. The game board is represented as a 3x3 grid, and players take turns marking their respective symbols ('X' or 'O') in the empty cells. The game continues until a player wins by having three of their symbols in a row horizontally, vertically, or diagonally, or if the board is completely filled without a winner, resulting in a draw.

### 2. How to Build and Run the Project:

To build and run the project, follow these steps:

- Copy and paste the provided C++ code into a C++ compiler or integrated development environment (IDE) like Code::Blocks, Visual Studio, or any other of your choice.

- Compile the code to generate the executable.

- Run the compiled executable.

- Follow the on-screen prompts to take turns entering the number corresponding to the cell where you want to place your symbol ('X' or 'O').

- The game will continue until a player wins or the game ends in a draw.

### 3. Additional Instructions or Dependencies:

- The code includes a simple clearing of the console screen using the `system("cls")` command. If you are using a different operating system or environment that requires a different command for clearing the screen, you may need to modify the `board()` function accordingly.

- Make sure your C++ compiler or IDE supports the use of the `<iostream>` library.

- The code does not have external dependencies, and it should run on any standard C++ environment.

- The game uses a simple array (`square`) to represent the Tic-Tac-Toe board. Each element of the array corresponds to a cell on the board.

- The game logic is contained in the `main()` function, `checkwin()` function for determining the game status, and the `board()` function for displaying the game board.

- The `checkwin()` function returns:
  - `1` if a player has won,
  - `0` if the game ends in a draw,
  - `-1` if the game is still in progress.

- The `board()` function displays the current state of the Tic-Tac-Toe board on the console.
