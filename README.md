# Battleship AI using Machine Learning
Using machine learning techniques, to play the game of battleship! Created in collaboration with Zayd and Barnabas.

## Battleship AI Agent Description

The modified battleship game occurs on a 10x10 grid map. A human player is given 1x length 2 ship, 2x length 3 ship, 1x length 4 ship, and 1x length 5 ship to place on the given grid map. The blue tiles mark the positions where the ships are placed, while the white tiles mark the positions where no ships are placed. The tiles which are struck (picked/guessed) are marked with a cross. The locations of the ships (blue tiles) are unknown to the agent. All tiles on the map appear white to the agent, with struck areas marked with a cross. However, if the agent strikes a ship tile, the tile will turn blue with a marked cross.

The objective of the agent is to destroy all five ships by striking (guessing/picking) all blue tiles in the grid map, while minimising the number of strikes. The game starts from the start position with an unmarked map grip with the human assigned ships, and ends at the goal position with all blue tiles marked with a cross.

The total number of game states is equal to the total number of combinations of strikes executed by the agent until all blue tiles are marked with a cross. The game state changes whenever the agent strikes a tile.
