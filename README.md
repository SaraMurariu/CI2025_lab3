# CI2025_lab3
Computational Intelligence Lab 3
# PATHFINDING ALGORITHMS COMPARISON

Comprehensive comparison of the performance, efficiency and scalability of several key pathfinding algorithms.

The comparison focuses on:
- Execution Time (Speed): time required to find the shortest path
- Nodes Expanded (Efficiency): amount of search space explored
- Optimality: ability to find the true shortest path

## ALGORITHMS
# ALGORITHMS FOR NON-NEGATIVE WEIGTHS

# Dijkstra's Algorithm
The standard, complete, and optimal Single-Source Shortest Path (SSSP) algorithm.
Highly efficient.

# A* Search
An informed SSSP algorithm that uses a heuristic function to guide the search toward the goal, minimizing search space.
Significantly faster in practice than Dijkstra's due to fewer nodes expanded.

Variants analyzed:
- A* with Euclidean heuristics
- A* with Manhattan heuristics
- A* with zero heuristics, making it mathematically equivalent to Dijkstra's algorithm.

# ALGORITHMS FOR NEGATIVE WEIGTHS
# Bellman-Ford Algorithm
The fundamental SSSP algorithm capable of handling negative edge weights.
Can reliably detect negative cycles, where the shortest path is unbounded.

# Johnson's Algorithm
It handles negative weights by running a pre-processing step to re-weight all edges to be non-negative.
it is only efficient when performing multiple shortest path queries on the same graph instance. For a single query, it is typically slower than Bellman-Ford.



