Breadth-First Search (BFS) Implementation in C

This project implements the Breadth-First Search (BFS) algorithm using an adjacency matrix representation of a graph in C programming language.

The program uses a queue (array-based implementation) to traverse the graph level by level.

📌 Description

In this program:

A graph is represented using an adjacency matrix.

A queue is implemented using an array.

A visited array is used to track visited vertices.

BFS traversal starts from a given source vertex.

The traversal order is printed.

🧠 What is Breadth-First Search (BFS)?

BFS is a graph traversal algorithm that explores all vertices:

Level by Level (or Layer by Layer)

It uses a Queue (FIFO) data structure.

📂 Data Structures Used
🔹 Queue (Array Implementation)
int queue[MAX];
int front = -1, rear = -1;
🔹 Visited Array
int visited[MAX];
🔹 Adjacency Matrix
int graph[MAX][MAX];
🔁 BFS Algorithm Steps

Enqueue the starting vertex.

Mark it as visited.

While queue is not empty:

Dequeue a vertex.

Print the vertex.

Enqueue all unvisited adjacent vertices.

Mark them as visited.

🖥️ Graph Used in Program

Number of vertices: 4

Adjacency Matrix:

0 1 1 0
1 0 1 1
1 1 0 0
0 1 0 0

Graph Representation:

0 -- 1
|    / \
2 --     3
▶️ Sample Output
BFS Traversal: 0 1 2 3
⚙️ How to Compile and Run
1️⃣ Compile
gcc bfs.c -o bfs
2️⃣ Run
./bfs
⏱️ Time & Space Complexity

Time Complexity: O(V²)
(Using adjacency matrix)

Space Complexity: O(V)

Where:

V = Number of vertices

📚 Concepts Covered

Graph Representation

Adjacency Matrix

Breadth-First Search (BFS)

Queue Implementation

Graph Traversal

⚠️ Limitations

Queue size is fixed (MAX = 10).

Not suitable for large graphs.

No input validation.

👨‍💻 Author

Ritik Chauhan

If you want, I can also provide:

BFS using adjacency list

DFS implementation

Comparison README (BFS vs DFS)

Menu-driven graph program
