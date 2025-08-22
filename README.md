# Artificial-and-Computational-Intelligence
The task involves designing a Problem Solving Agent (PSA) that can dynamically accept user input to define the problem, build the environment, and compute the path, cost, and solution efficiently.
________________________________________
Artificial and Computational Intelligence –
Project Overview
This project focuses on problem-solving using search algorithms, specifically Informed Search (like A*) and Local Search (like Hill Climbing). The task involves designing a Problem Solving Agent (PSA) that can dynamically accept user input to define the problem, build the environment, and compute the path, cost, and solution efficiently.
The project demonstrates core concepts of Artificial Intelligence such as state space representation, transition models, successor functions, goal testing, and pathfinding, while applying appropriate data structures and algorithms.
________________________________________
Key Objectives
•	Represent the problem environment clearly using graphs or matrices.
•	Design and implement two algorithms for pathfinding:
o	Algorithm 1: An informed search strategy (e.g., A* Search or Greedy Best-First Search).
o	Algorithm 2: A local search strategy (e.g., Hill Climbing or Simulated Annealing).
•	Dynamically handle user input for starting and goal states.
•	Evaluate and compare algorithm performance based on time and space complexity.
________________________________________
PEAS Description
Component	Description
Performance Measure	Shortest path cost, minimum computation time, and efficiency of search.
Environment	Graph or matrix representing states and transitions with associated costs.
Actuators	Functions that select the next node or path during search.
Sensors	Current state, goal state, and possible transitions from the current node.
________________________________________
Key Components
1. Environment Setup
•	Graph representation using Python dictionaries or adjacency matrices.
•	Clear variable declarations for states, transitions, and costs.
________________________________________
2. Transition Model
•	Implements the successor function to determine possible next states from a given node.
•	Includes dynamic cost assignment to edges, enabling realistic graph traversal.
________________________________________
3. Goal Test
•	Checks if the current node matches the goal node.
•	Handles dynamic inputs to allow flexible state selection during runtime.
________________________________________
4. Search Algorithms
Algorithm 1 – Informed Search
•	Likely A* Search or Greedy Best-First Search.
•	Uses:
o	g(n): Cost from start to the current node.
o	h(n): Heuristic estimate of the cost to the goal.
o	f(n) = g(n) + h(n) for optimal path computation.
Algorithm 2 – Local Search
•	Implements techniques like Hill Climbing or Simulated Annealing.
•	Iteratively improves the solution based on local neighbor states but may face challenges like getting stuck in local minima.
________________________________________
5. Dynamic Inputs
•	Accepts user input for:
o	Start state
o	Goal state
•	Displays available states to ensure valid selection.
________________________________________
6. Outputs
•	Path taken from start state to goal state.
•	Cost of the path and number of steps taken.
•	Visual or printed output of the solution path for clarity.
________________________________________
Comparative Analysis
After implementing and running both algorithms, the following metrics are compared:
•	Path Cost
•	Execution Time
•	Memory Usage
•	Optimality and Efficiency
________________________________________
Example Findings
•	Informed Search (A*) usually yields optimal paths with higher computational cost but better accuracy.
•	Local Search (Hill Climbing) is faster but may not always find the global optimum due to local minima or plateaus.
________________________________________
Expected Deliverables
1.	Clean and documented code with distinct sections:
o	Initial state setup
o	Transition and cost matrix
o	Successor function
o	Goal testing
o	Implementation of algorithms
2.	Performance Analysis of both algorithms.
3.	Summary of results in ≤3 lines with insights on which approach is better for the given problem.
________________________________________
Skills Highlighted
•	Python programming with data structures (lists, dictionaries, queues, and priority queues).
•	Implementation of AI search algorithms.
•	Problem formulation and dynamic environment modeling.
•	Performance evaluation and complexity analysis.

