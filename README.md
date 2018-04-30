# A* to solve N-Puzzle Game

The goal of this project is to code a solution to the 8-puzzle, and its natural generalizations by applying the A* search algorithm with various admissible heuristics.

Description of the 8-puzzle game:
The 8-puzzle is a sliding tile game whose larger cousin, the 15-puzzle, was invented in the 1870s by Noyce Palmer Chapman. The game board consists of eight sliding tiles bearing the numbers 1-8 that move on a 3 x 3 grid. When the puzzle is in the solved state state, there is a blank space in the top left-hand corner, followed by the tiles in increasing numerical order from left to right, top to bottom. Any tile horizontally or vertically adjacent to the blank space can be moved into the space, effectively swapping the position of that tile and the space. From a scrambled configuration of the tiles, the aim is to repeatedly move appropriate tiles into the blank space until the tiles and blank square are restored to their solved configuration. This problem easily generalizes to boards of size n^2 - 1, for any natural number n > 3.
