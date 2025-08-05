4Connect4
4Connect4 is a customizable, multi-player Connect Four game implemented in Java with a graphical user interface (GUI) using Swing. The project supports 2 to 4 players, variable grid sizes (up to 16x16), and a configurable number of connected pieces required to win.

Features
Customizable Gameplay: Choose grid size, number of players (2–4), and win condition.
Graphical User Interface: Intuitive GUI for easy play, including clickable column buttons and a live scoreboard.
Game Logic: Robust backend logic for handling turns, win/tie detection, and player statistics.
Replay Support: Option to replay the game after a win or tie without restarting the application.

How to Run

Compile the source files:
  javac -d bin src/*.java
  
Run the game:
  java -cp bin ConnectGUI [gridSize] [winConnectedPieces] [numPlayers]

Example: java -cp bin ConnectGUI 8 4 2
If no arguments are provided, defaults are used (8x8 grid, 4 to win, 2 players).
