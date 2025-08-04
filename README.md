 # Of course 

***

## Divide and Conquer

The **_Divide and Conquer_** paradigm is a powerful strategy for algorithm design that involves breaking a problem into smaller subproblems, solving them recursively, and then combining their results. This approach often leads to significant efficiency gains over simpler methods, which can be formally analyzed. The performance of these recursive algorithms is typically determined using the **_Master Theorem_**.

**Key Algorithms and Concepts Covered:**
* **_Master Theorem_**
* **_Exponentiation by Squaring_**
* **_Merge Sort_**
* **_Quick Sort_**
* **_Quickselect_**
* **_Maximum Subarray Sum_**
* **_Karatsuba's Algorithm_**
* **_Closest Pair of Points_**

---

## Dynamic Programming

**_Dynamic Programming_** is an optimization technique for solving complex problems by breaking them into simpler, overlapping subproblems. It works by solving each subproblem just once and storing its solution, typically in a table, to avoid redundant computations. This method is effective for problems that exhibit optimal substructure and overlapping subproblems.

**Key Algorithms and Concepts Covered:**
* **_Fibonacci Numbers_**
* **_Assembly-Line Scheduling_**
* **_Longest Common Subsequence (LCS)_**
* **_0-1 Knapsack Problem_**
* **_Matrix-Chain Multiplication_**
* **_Corporate Party Planning_**
* **_Edit Distance (Levenshtein)_**

---

## Greedy Algorithms

The **_Greedy Algorithm_** paradigm is an approach for solving optimization problems by making a sequence of locally optimal choices at each stage. The core idea is that making the choice that seems best at the moment will lead to a global optimum. For this to be effective, the problem must exhibit the greedy-choice property, and the algorithm's optimality must be formally proven.

**Key Algorithms and Concepts Covered:**
* **_Fractional Knapsack Problem_**
* **_Activity-Selection Problem_**
* **_Huffman Codes_**
* **_Coin Change Problem_**
* **_Proof of Optimality_**

---

## Graph Algorithms

This lesson explores fundamental graph algorithms for solving two major optimization problems: finding a **_Minimum Spanning Tree (MST)_** and finding the **_Shortest Path_**. These problems are central to network design and routing, with solutions employing both greedy and dynamic programming strategies. The choice of algorithm depends on the graph's properties, such as edge weights.

**Key Algorithms and Concepts Covered:**
* **_Kruskal's Algorithm_**
* **_Prim's Algorithm_**
* **_Union-Find Data Structure_**
* **_Dijkstra's Algorithm_**
* **_Bellman-Ford Algorithm_**
* **_Floyd-Warshall Algorithm_**

---

## Network Flow

This lesson covers the **_Maximum Flow Problem_**, which models the maximum rate at which a commodity can move from a source to a sink in a capacity-constrained network. The central solution method is the **_Ford-Fulkerson algorithm_**, which iteratively increases flow through the network. Its correctness is guaranteed by the fundamental **_Max-Flow Min-Cut Theorem_**.

**Key Algorithms and Concepts Covered:**
* **_Ford-Fulkerson Algorithm_**
* **_Augmenting Path_**
* **_Residual Graph_**
* **_Max-Flow Min-Cut Theorem_**
* **_Edmonds-Karp Algorithm_**
* **_Maximum Bipartite Matching_**
* **_Circulation with Demands_**

---

## NP and NP-Completeness

This lesson introduces the theory of computational intractability, focusing on the classes **_P_** (solvable in polynomial time) and **_NP_** (verifiable in polynomial time). It explores the famous **_P vs. NP_** problem, which questions whether every problem with an easily verifiable solution can also be solved efficiently. The concept of **_NP-Completeness_** is used to classify the hardest problems in NP.

**Key Algorithms and Concepts Covered:**
* **_Class P_**
* **_Class NP_**
* **_Polynomial-Time Reduction_**
* **_NP-Complete_**
* **_Circuit-SAT_**
* **_3-SAT_**
* **_CLIQUE_**
* **_SUBSET-SUM_**
