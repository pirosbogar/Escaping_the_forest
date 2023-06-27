# Escaping_the_forest
A jump game.
 
The problem:
In a mystical forest, there is a series of enchanted stepping stones and treacherous quicksand pits. A brave adventurer must navigate through this forest to reach a hidden treasure. The forest has a linear path with multiple sections, each section consisting of either a stepping stone or quicksand. The goal is to find the minimum number of moves and the exact path to reach the treasure.

For example, consider the forest represented by the following sequence:

[1, 0, 0, 0, 0, 1, 1, 0, 1, 0, 0, 0, 1, 1, 1, 1, 0, 1] where 1 means stepping stones and 0 means quicksand, the length of this specific example is 18 units.
The adventurer can leap exactly 1, 2, 3 or 5 units forward.

Compute the minimum number of moves required and determine the precise path to successfully navigate the forest based on the provided representation!

Examples:
[1, 1, 0, 1, 0, 1, 1, 0, 0, 0, 1] - Solution: 2 moves, Path: [1, 6, 11]
[1, 1, 0, 1, 0, 1, 1] - Solution: 2 moves, Path: [1, 6, 7]
[1, 1, 0, 0, 0, 1, 0, 1, 1, 0, 0, 0, 0, 0, 1, 1, 0, 1] - Solution: No solution, Path: [1]
[1, 1, 1, 1, 1, 0, 1, 0, 0, 0, 1] - Solution: 3 moves, Path: [1, 4, 7, 11]
Limitations:
The forest representation always starts and ends with a 1. The first element represents the starting point, and the last element represents the endpoint.
If the adventurer lands on a stepping stone that allows them to jump beyond the endpoint, it is considered a valid solution (see example 4).
If there is no valid path to reach the treasure, the path should be: Solution: No solution, Path: [1]
