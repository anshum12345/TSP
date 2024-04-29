**Traveling Salesman Problem (TSP) Solver using Simulated Annealing**

This repository contains a simple yet effective implementation of simulated annealing to solve the Traveling Salesman Problem (TSP). The solution process begins by utilizing a 2-opt greedy algorithm to construct an initial solution. Simulated annealing is then applied to refine the initial solution, aiming to minimize the total distance traveled by the salesman.

**Key Features:**
- *2-opt Greedy Algorithm*: Generates an initial solution by iteratively selecting the nearest unvisited city to construct a route.
- *Simulated Annealing*: Optimizes the initial solution using simulated annealing, allowing for occasional uphill moves to escape local optima.
- *Visualization*: Provides visualization of the resulting route on a scatter plot, showcasing the path taken by the salesman to visit each city exactly once.
- *Fitness Tracking*: Tracks the objective value (total distance) through iterations, allowing for analysis of the optimization process.

**Example Usage:**
- An example of the resulting route on a TSP with 50 nodes is included, along with the fitness (objective value) plotted through iterations.

**Contributions:**
Contributions, feedback, and suggestions for improvements are welcome! Feel free to fork this repository, make enhancements, and submit pull requests.

**License:**
This project is licensed under the [MIT License](LICENSE).

**Authors:**
Made by Anshum Dwivedi & Aman Shukla.

**Note:**
This implementation provides decent results for solving TSP instances using simulated annealing. Further optimizations and parameter adjustments can be explored to improve solution quality or computational efficiency based on specific problem requirements.