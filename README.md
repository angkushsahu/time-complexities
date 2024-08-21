# Time Complexities of Operations in Various C++ Data Structures

This table summarizes the best, average, and worst-case time complexities for insertion, deletion, updating, and reading a value in various C++ data structures.

| Data Structure   | Operation | Best Case Complexity | Average Case Complexity | Worst Case Complexity |
|------------------|-----------|----------------------|-------------------------|-----------------------|
| **Unordered Map**| Insertion | O(1)                 | O(1)                     | O(N)                   |
|                  | Deletion  | O(1)                 | O(1)                     | O(N)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(N)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(N)                   |
| **Ordered Map**  | Insertion | O(log N)             | O(log N)                 | O(log N)               |
|                  | Deletion  | O(log N)             | O(log N)                 | O(log N)               |
|                  | Updating  | O(log N)             | O(log N)                 | O(log N)               |
|                  | Reading   | O(log N)             | O(log N)                 | O(log N)               |
| **Unordered Set**| Insertion | O(1)                 | O(1)                     | O(N)                   |
|                  | Deletion  | O(1)                 | O(1)                     | O(N)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(N)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(N)                   |
| **Ordered Set**  | Insertion | O(log N)             | O(log N)                 | O(log N)               |
|                  | Deletion  | O(log N)             | O(log N)                 | O(log N)               |
|                  | Updating  | O(log N)             | O(log N)                 | O(log N)               |
|                  | Reading   | O(log N)             | O(log N)                 | O(log N)               |
| **Vector**       | Insertion | O(1) (amortized)     | O(N) (at end)            | O(N) (at position)     |
|                  | Deletion  | O(1) (at end)        | O(N)                     | O(N)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(1)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(1)                   |
| **Array**        | Insertion | O(N)                 | O(N)                     | O(N)                   |
|                  | Deletion  | O(N)                 | O(N)                     | O(N)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(1)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(1)                   |
| **Stack**        | Insertion | O(1)                 | O(1)                     | O(1)                   |
|                  | Deletion  | O(1)                 | O(1)                     | O(1)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(1)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(1)                   |
| **Deque**        | Insertion | O(1)                 | O(1)                     | O(1)                   |
|                  | Deletion  | O(1)                 | O(1)                     | O(1)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(1)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(1)                   |
| **Queue**        | Insertion | O(1)                 | O(1)                     | O(1)                   |
|                  | Deletion  | O(1)                 | O(1)                     | O(1)                   |
|                  | Updating  | O(1)                 | O(1)                     | O(1)                   |
|                  | Reading   | O(1)                 | O(1)                     | O(1)                   |

### Notes:
- **Unordered structures (maps and sets)** rely on hashing, which typically provides O(1) average time but potentially O(N) in the worst case due to collisions.
- **Ordered structures (maps and sets)** are usually implemented as balanced trees (like Red-Black Trees), giving O(log N) for insertions, deletions, updates, and reads.
- **Vectors** have O(1) for amortized insertion at the end but O(N) when resizing or inserting at arbitrary positions.
- **Arrays** have O(1) access time for reading and updating, but O(N) for insertion and deletion due to the need to shift elements.
- **Stacks, queues, and deques** typically allow O(1) operations for insertion, deletion, and access due to their specific use cases.
