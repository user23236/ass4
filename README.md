# README Analysis Answers

## How does graph size affect BFS and DFS performance?

As graph size increases, traversal time also increases because more vertices and edges must be visited.

---

## Which traversal was faster?

DFS was slightly faster in most experiments because it uses recursion and fewer queue operations.

---

## Do results match O(V + E)?

Yes. Both algorithms visit each vertex and edge once, which matches the expected time complexity: O(V + E)

## How does graph structure affect traversal order?

BFS explores level-by-level, while DFS explores deeply before backtracking. Different edge connections change traversal order.

---

## When is BFS preferred over DFS?

BFS is preferred when finding the shortest path in unweighted graphs.

---

## What are limitations of DFS?

DFS can go very deep and may cause stack overflow in very large graphs.

---

# Algorithms

## Breadth-First Search (BFS)

BFS explores the graph level by level using a queue.

### Steps
1. Start from a vertex
2. Mark it as visited
3. Add neighbors to queue
4. Repeat until queue is empty

### Time Complexity

O(V + E)

### Use Cases
- Shortest path
- Network traversal
- Social networks

---

## Depth-First Search (DFS)

DFS explores one branch deeply before backtracking.

### Steps
1. Visit current vertex
2. Mark visited
3. Recursively visit neighbors

### Time Complexity

O(V + E)

### Use Cases
- Maze solving
- Cycle detection
- Topological sorting

---

# Experimental Results

## Execution Time Comparison

| Graph Size | BFS Time (ns) | DFS Time (ns) |
|------------|---------------|---------------|
| 10         | 1219700       | 392300        |
| 30         | 780700        | 745200        |
| 100        | 2139000       | 1882100       |

---

# Observations

- Execution time increased as graph size increased.
- DFS was slightly faster in most tests.
- Both algorithms demonstrated linear growth behavior consistent with O(V + E).
- In simple linear graphs, BFS and DFS produced similar traversal orders.
- In branching graphs, traversal order differences became more visible.

---

# Screenshots

## Graph Output

<img width="292" height="364" alt="Снимок экрана 2026-05-22 214330" src="https://github.com/user-attachments/assets/8f0f1f46-c48e-46cc-aab3-dfba3d763c67" />


## BFS Traversal

<img width="234" height="92" alt="image" src="https://github.com/user-attachments/assets/aea7edfd-c510-457b-bf7a-96be1d7be6e8" />


## DFS Traversal

<img width="217" height="98" alt="image" src="https://github.com/user-attachments/assets/ea44a9e8-2b99-4d67-a9e7-d0277116b7f7" />


## Performance Results

<img width="803" height="319" alt="image" src="https://github.com/user-attachments/assets/a88e198f-21a2-467c-8590-0b3dd98be7da" />
<img width="1729" height="363" alt="image" src="https://github.com/user-attachments/assets/748e30b0-1adf-4bc1-99d7-61861f4d4785" />


---

# Reflection

Through this assignment, I learned how graph traversal algorithms work and how graph structure affects traversal behavior.

I understood the difference between BFS and DFS, especially how BFS explores level-by-level while DFS explores deeply before backtracking.

Didn't face any challenge during this assignment.

  
