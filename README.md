This R script simulates the classic game of Battleship, where two players take turns attempting to sink each other's fleet of ships (using simple random sampling without replacement) hidden on a 10x10 grid. 
The game is played for a specified number of rounds, with each player aiming to be the first to sink all of their opponent's ships.

Game Setup:
The game board is a 10x10 grid, represented by rows labeled A-J and columns labeled 1-10. Each player has a fleet consisting of 5 ships of varying lengths (2,3,3,4,and 5 units). 
Ships are placed randomly on the board without overlapping.

Gameplay:
Players take turns firing shots at their opponent's board by selecting a random cell. Each shot is checked to see if it hits (a ship) or misses (empty water).
The game continues until one player sinks all of their opponent's ships.

Tracking and Display:
The game keeps track of the number of shots taken in each round.
The results of each game, including the game number, winner, and total shots taken, are stored in a data frame for easy reference and analysis.

Statistics:
After playing multiple games, the script prints the total wins for each player and the shots taken per game, providing a comprehensive overview of the game results.
