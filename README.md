## Divide and Conquer

The **_Divide and Conquer_** paradigm is a powerful strategy for algorithm design that involves breaking a problem into smaller subproblems, solving them recursively, and combining the results.

Here are the key algorithms and concepts covered:

* **_Master Theorem_**: Provides a formula to quickly determine the time complexity of recursive, divide-and-conquer algorithms.
* **_Exponentiation by Squaring_**: An efficient algorithm that computes large integer powers in logarithmic time.
* **_Merge Sort_**: A stable sorting algorithm that sorts an array by recursively splitting it in half and merging the sorted subarrays.
* **_Quick Sort_**: An efficient, in-place sorting algorithm that partitions an array around a pivot element and sorts the partitions recursively.
* **_Quickselect_**: A selection algorithm that finds the k-th smallest element in a collection in expected linear time.
* **_Maximum Subarray Sum_**: An optimized divide-and-conquer approach to find the contiguous subarray with the largest sum in linear time.
* **_Karatsuba's Algorithm_**: A fast multiplication algorithm that improves upon the classic method by reducing the number of recursive multiplications.
* **_Closest Pair of Points_**: A geometric algorithm that efficiently finds the two points with the minimum distance between them in a plane.


## Dynamic Programming

**_Dynamic Programming_** is an optimization technique that solves complex problems by breaking them down into simpler overlapping subproblems and storing their solutions to avoid redundant computations.

Here are the key algorithms and concepts covered:

* **_Fibonacci Numbers_**: Introduces DP by showing how storing results (**_memoization_**) transforms an exponential recursive solution into a linear one.
* **_Assembly-Line Scheduling_**: Finds the fastest path through a multi-line factory by building a solution from optimal choices at each station.
* **_Longest Common Subsequence (LCS)_**: A classic problem that finds the longest subsequence shared between two strings using a 2D table to track optimal substructures.
* **_0-1 Knapsack Problem_**: Determines the most valuable combination of items to include in a bag of limited weight capacity, solved with a pseudo-polynomial time DP approach.
* **_Matrix-Chain Multiplication_**: Finds the most efficient order to multiply a chain of matrices by determining the optimal parenthesization.
* **_Corporate Party Planning_**: A DP-on-trees problem that selects nodes to maximize a value subject to parent-child constraints.
* **_Edit Distance (Levenshtein)_**: Calculates the minimum number of edits (insert, delete, substitute) needed to change one string into another, widely used in NLP.



## Greedy Algorithms

The **_Greedy Algorithm_** paradigm is an approach for solving optimization problems by making a sequence of locally optimal choices at each stage with the hope of finding a global optimum.

Here are the key algorithms and concepts covered:

* **_Fractional Knapsack Problem_**: An optimization problem solved by greedily selecting items with the highest value-to-weight ratio to maximize total value.
* 
* **_Activity-Selection Problem_**: A scheduling problem solved by greedily choosing the activity with the earliest finish time to maximize the number of compatible activities.
* 
* **_Huffman Codes_**: A classic data compression algorithm that uses a greedy strategy to build an optimal prefix-free binary code tree for characters based on their frequency.
* 
* **_Coin Change Problem_**: A classic example used to demonstrate that while a greedy approach can be optimal for certain coin systems, it can fail for others.
* 
* **_Proof of Optimality_**: Greedy algorithms require a formal proof, often by contradiction, to show that the local choices lead to a global optimum.



## Graph Algorithms

This lesson explores fundamental graph algorithms for solving two major optimization problems: finding the **_Minimum Spanning Tree_** to connect all vertices with minimum cost, and finding the **_Shortest Path_** between vertices.

Here are the key algorithms and concepts covered:

* **_Kruskal's Algorithm_**: A greedy approach that builds a Minimum Spanning Tree (MST) by iteratively adding the lowest-weight edge that doesn't form a cycle.
* **_Prim's Algorithm_**: A greedy approach that builds an MST by growing a single tree, always adding the cheapest edge that connects the tree to a new vertex.
* **_Union-Find Data Structure_**: An auxiliary data structure used with Kruskal's algorithm to efficiently track connected components and detect cycles.
* **_Dijkstra's Algorithm_**: A classic algorithm for finding the single-source shortest paths in a weighted graph, provided all edge weights are non-negative.
* **_Bellman-Ford Algorithm_**: A single-source shortest path algorithm that uses dynamic programming to handle graphs with negative edge weights and can detect negative cycles.
* **_Floyd-Warshall Algorithm_**: A dynamic programming algorithm that efficiently solves the all-pairs shortest path problem, also capable of handling negative weights.
