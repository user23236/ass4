#README Analysis Answers

##How does graph size affect BFS and DFS performance?

As graph size increases, traversal time also increases because more vertices and edges must be visited.

##Which traversal was faster?

DFS was slightly faster in most experiments because it uses recursion and fewer queue operations.

##Do results match O(V + E)?

Yes. Both algorithms visit each vertex and edge once, which matches the expected time complexity: O(V+E)

##How does graph structure affect traversal order?

BFS explores level-by-level, while DFS explores deeply before backtracking. Different edge connections change traversal order.

##When is BFS preferred over DFS?

BFS is preferred when finding the shortest path in unweighted graphs.

##What are limitations of DFS?

DFS can go very deep and may cause stack overflow in very large graphs.

BFS Explanation for README
Breadth-First Search (BFS)

BFS explores vertices level-by-level using a queue.

Steps:
Start from a vertex
Mark it visited
Add neighbors to queue
Repeat until queue is empty
Time Complexity

O(V+E)

Use Cases
Shortest path
Network traversal
Social connections
DFS Explanation for README
Depth-First Search (DFS)

DFS explores one path deeply before backtracking.

Steps:
Visit current node
Mark visited
Recursively visit neighbors
Time Complexity

O(V+E)

Use Cases
Maze solving
Cycle detection
Topological sorting
