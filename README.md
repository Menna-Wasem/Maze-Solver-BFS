Maze Solver Using BFS

1. Project Idea

This project is a Maze Solver implemented using Python. It finds a path from a start position to a goal position in a maze while avoiding obstacles (walls).

2. Algorithm Used

The project uses Breadth-First Search (BFS) to explore the maze level by level until the goal is reached.

BFS uses a FIFO Queue to explore neighboring cells and find the shortest path when all movements have equal cost.

3. Problem Formulation

- State: The current position (row, column) in the maze.
- Initial State: (0, 0).
- Goal State: (6, 6).
- Actions: Move Up, Down, Left, or Right.
- Action Cost: 1 for each movement.
- Obstacles: Cells containing 1 represent walls, while cells containing 0 represent free paths.

4. Technologies Used

- Python
- Google Colab
- NumPy
- Matplotlib

5. How to Run the Project

1. Open the Google Colab notebook.
2. Run all code cells in order.
3. View the maze visualization, the solution path, and the search results.

6. Results

The program displays:

- Whether a solution was found.
- The shortest path.
- The path cost.
- The number of explored nodes.
- A visualization of the maze and the solution path.

The project also includes a test case where no valid path exists.
