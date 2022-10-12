# APCS-Project-Game-of-Life-

This is the project i chose to do for teh AP Computer Science Principles performance Task

Conway's Game of Life is an example of a cellular automaton simulation.

The first initial gorup of living and dead cells are called the first generation. After that, each generation will have either a set of new cells, dead cells, 
or a combination of cells from the previous generation based on three rules. Those three rules are: 

1. A dead cell that has 3 living cells around it will become alive. 
2. A living cell that has 2 or 3 living cells around it will survive.
3. A living cell that has <2 or >3 neighbors will become dead.

John Conway, the creator of this simulation, noted that there is no simple algorithm to detirmine if the first generation will evolve continuously, die off or 
fall into a steady and repeating pattern. 

Conway's Game of Life can also be used to represent logic and logic gates. Therefore, others have designed patterns to perform computational tasks 
within the confines of the Game of Life. Those logic gates and computational tasks are not shown in my implementation of the game.
