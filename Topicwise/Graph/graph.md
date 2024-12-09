# When to Use Graphs

## On Matrices

Graphs can be used to represent matrices for tasks that involve connectivity, traversal, or mapping relationships between cells or elements.

---

# When to Use BFS

1. **Simultaneous Neighbor Traversal:**
   - BFS is ideal when approaching neighboring nodes simultaneously (e.g., problems like rotten oranges where multiple nodes spread an effect).
2. **Level-Order Traversal:**
   - Use BFS for tasks where a level-wise exploration of nodes is required.
3. **Non-Simultaneous Operations:**
   - BFS can also be used when counting simultaneous operations is not necessary.

---

# When to Use DFS

1. **Non-Simultaneous Operations:**
   - DFS is suitable when we do not need to count simultaneous operations.
2. **Depth-Based Traversal:**
   - Use DFS when you need to explore paths or traverse as deeply as possible before backtracking.

# Tips

1. **In case of matrix, We often need to find the starting point ( could be many ) in many questions from where we will start the DFS or BFS**

# Bipartite Graph

- **Adjacent nodes will not have the same colors**

# Topological Sort - Only for DAG

- A sorting where if there is an edge from A to B, A will appear before B in sorting
- Only applicable to Directed Acyclic Graphs