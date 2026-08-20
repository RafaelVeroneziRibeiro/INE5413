# Activity A1: Graph Representation and Basic Algorithms

##  Description
This activity focuses on building a foundational graph library and implementing fundamental traversal and shortest-path algorithms[cite: 20]. The implementation models an undirected, weighted graph $G(V,E,w)$ where operations are optimized to achieve $O(1)$ time complexity whenever possible.

##  Implemented Features

### 1. Graph Data Structure
A custom class to represent graphs, capable of loading data from `.net` text files. It includes methods for checking adjacency, retrieving edge weights, getting vertex degrees, and listing neighbors.

### 2. Implemented Algorithms
*   **Breadth-First Search (BFS):** Explores the graph level by level starting from a given source vertex.
*   **Eulerian Cycle:** Determines if the graph contains an Eulerian cycle and prints the sequence of vertices if it exists.
*   **Single-Source Shortest Path:** Uses Dijkstra's or Bellman-Ford's algorithm to find the shortest path and distance from a source vertex to all other vertices.
*   **All-Pairs Shortest Path:** Uses the Floyd-Warshall algorithm to compute the shortest distances between every pair of vertices in the graph.

## ⚙️ How to Run

To run the programs, compile the specific `.cpp` file and pass the required arguments via the terminal.

