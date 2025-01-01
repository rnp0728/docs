<p><a target="_blank" href="https://app.eraser.io/workspace/9QczxtLdfMEE9SCBgOLs" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

# Types of Data Structures
## 1. Linear Data Structures
These structures organize data in a linear order:

- **Array**
    - Stores elements in contiguous memory locations.
    - All elements must be of the same type.
    - Accessed via indices (e.g., `arr[0]` ).
    - Example: `[1, 2, 3, 4]` .
- **Linked List**
    - A series of nodes where each node contains data and a reference to the next node.
    - Types:
        - **Singly Linked List**: Each node points to the next.
        - **Doubly Linked List**: Nodes have pointers to both the next and previous nodes.
        - **Circular Linked List**: The last node points back to the first node.
- **Stack**
    - Follows LIFO (Last In, First Out) principle.
    - Operations: `push`  (add), `pop`  (remove), and `peek`  (view top element).
    - Example: Undo functionality in text editors.
- **Queue**
    - Follows FIFO (First In, First Out) principle.
    - Types:
        - **Simple Queue**: Basic implementation.
        - **Circular Queue**: The rear connects back to the front.
        - **Priority Queue**: Elements are dequeued based on priority.
        - **Double-Ended Queue (Deque)**: Elements can be added or removed from both ends.
---

## 2. Non-Linear Data Structures
These structures do not organize data sequentially:

- **Trees**
    - Hierarchical structure with a root node and child nodes.
    - Types:
        - **Binary Tree**: Each node has up to two children.
        - **Binary Search Tree (BST)**: Left child < Parent < Right child.
        - **AVL Tree**: A balanced BST.
        - **Red-Black Tree**: Self-balancing BST with color-coded nodes.
        - **Heap**: A complete binary tree (Min-Heap or Max-Heap).
        - **B-Tree**: Balanced search tree for efficient storage.
        - **B+ Tree**: Variation of B-Tree optimized for range queries.
        - **Trie**: Specialized tree for storing strings or sequences.
- **Graphs**
    - Consists of vertices (nodes) and edges (connections).
    - Types:
        - **Directed Graph (Digraph)**: Edges have directions.
        - **Undirected Graph**: Edges do not have directions.
        - **Weighted Graph**: Edges have weights.
        - **Unweighted Graph**: Edges have no weights.
        - **Cyclic Graph**: Contains cycles.
        - **Acyclic Graph**: No cycles.
        - **Complete Graph**: Every pair of vertices is connected.
---

## 3. Hash-Based Data Structures
Used for efficient data retrieval using keys:

- **Hash Table**
    - Stores key-value pairs for fast lookups.
    - Collisions are handled using techniques like chaining or open addressing.
- **Hash Map**
    - Similar to hash tables but may support null keys/values depending on the language.
- **Hash Set**
    - Stores unique elements with no duplicates.
---

## 4. Specialized Data Structures
Used for specific applications:

- **Matrix**
    - A 2D array representation often used for mathematical computations.
    - Example: Grids in games or adjacency matrices in graphs.
- **Heap**
    - Specialized binary tree for priority-based operations.
    - Used in algorithms like Dijkstra's.
- **Priority Queue**
    - Similar to a queue but elements are dequeued based on priority.
- **Disjoint Set (Union-Find)**
    - Tracks a set of elements partitioned into disjoint subsets.
    - Used in graph algorithms like Kruskal's MST.
- **Bloom Filter**
    - Space-efficient probabilistic structure for membership testing.
    - May produce false positives but not false negatives.
---

## 5. String Data Structures
Used for handling and manipulating strings:

- **Suffix Tree**
    - A compressed trie for storing all suffixes of a string.
    - Useful in substring search.
- **Suffix Array**
    - A sorted array of all suffixes of a string.
    - More memory-efficient than suffix trees.
- **KMP Table (for pattern matching)**
    - Used in the Knuth-Morris-Pratt string-matching algorithm to optimize pattern searches.
---

## 6. File Data Structures
Used in file systems and storage:

- **Indexed File**
    - Uses an index to locate records quickly.
- **Sequential File**
    - Stores records in a sequential order.
- **Hashed File**
    - Uses a hash function to determine record placement.
- **B+ Tree Indexing**
    - Used in databases for efficient range queries and indexing.




<!--- Eraser file: https://app.eraser.io/workspace/9QczxtLdfMEE9SCBgOLs --->