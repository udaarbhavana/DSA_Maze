# DSA_Maze

Objective:
This project generates a random maze, finds a path from the start to the end, and visualizes the maze and path in the terminal.

Specifications:
Input:
1. Size of the maze ( ).
2. Users choose to either print the path, generate another puzzle, or exit the game.
Output:
1. A visual representation of the generated maze in the terminal 2D
2. A visual representation of the path from start to end, if it exists.

Rules:
1. The maze is represented as a array where each cell can be either a wall or an open space.
2. The top-left corner is the start ( ) and the bottom-right corner is the end ( ).
3. The application should provide options to print the path, generate another puzzle, or exit the game.
4. The number of random walls should be restricted to be less than or equal to % of the total cells to increase the likelihood of a solvable maze.

Code Structure:
Maze Generation Function: Generates a random maze and returns it as a array.
Maze Printing Function: Prints the maze in the terminal.
Pathfinding Function: Finds a path from the start to the end using a suitable algorithm like BFS or DFS.
Path Printing Function: Prints the path in a readable format.
Path Marking Function: Marks the path on the maze for visualization.

