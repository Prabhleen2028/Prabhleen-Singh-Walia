18. AVL Trees
Question Description: Implement an AVL Tree, a self-balancing Binary Search Tree. After insertion or deletion, calculate the balance factor of affected nodes and perform rotations when necessary to maintain a balance factor of \(-1\), \(0\), or \(+1\).

Test Cases:
- Test Case 1: Insert nodes that cause a Left-Left (LL) imbalance.
  - Input Sequence: insert(30), insert(20), insert(10)
  - Expected Output (preorder after rotation): 20 10 30
  - Expected Result: The tree becomes balanced after a right rotation.
- Test Case 2: Insert nodes that cause a Right-Right (RR) imbalance.
  - Input Sequence: insert(10), insert(20), insert(30)
  - Expected Output (preorder after rotation): 20 10 30
  - Expected Result: The tree becomes balanced after a left rotation.
Time Complexity:
- Insertion: \(O(\log n)\)
- Searching: \(O(\log n)\)
- Deletion: \(O(\log n)\)
- Single Rotation (left or right): \(O(1)\)
- Traversal: \(O(n)\)
- Space Complexity: \(O(n)\)
