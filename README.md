This project implements **Prim's Algorithm** in C to find the **Minimum Spanning Tree (MST)** of a weighted undirected graph.

The graph is represented using an **Adjacency Matrix**.

---

 Concept Overview

 Minimum Spanning Tree (MST)

A Minimum Spanning Tree of a graph is:

- A subset of edges
- That connects all vertices
- Without forming cycles
- With the minimum possible total edge weight

---

 Prim's Algorithm

Prim’s Algorithm is a **greedy algorithm** used to construct the MST.

It works by:

1. Starting from any vertex (here vertex 0).
2. Selecting the minimum weight edge that connects a visited vertex to an unvisited vertex.
3. Adding that edge to the MST.
4. Repeating until all vertices are included.

---

 🛠 Program Features

- Uses adjacency matrix representation
- Implements greedy approach
- Finds MST for a connected weighted graph
- Displays edges included in MST
- Displays corresponding weights


Number of vertices: 5

Adjacency Matrix:
