17. Binary Search Tree (BST)
Question Description: Implement a Binary Search Tree in which each node's left subtree contains smaller keys and its right subtree contains larger keys. Support insertion, searching, deletion, and inorder traversal.

Test Cases:
- Test Case 1: Insert elements into the BST.
  - Input Sequence: insert(50), insert(30), insert(70), insert(20), insert(40), insert(60), insert(80)
  - Expected Inorder Output: 20 30 40 50 60 70 80
- Test Case 2: Search for an existing element.
  - Operation: search(60)
  - Expected Output: Element found
- Test Case 3: Delete a leaf node.
  - Operation: delete(20)
  - Expected Inorder Output: 30 40 50 60 70 80
Time Complexity:
- Insertion: Average \(O(\log n)\); worst \(O(n)\)
- Searching: Average \(O(\log n)\); worst \(O(n)\)
- Deletion: Average \(O(\log n)\); worst \(O(n)\)
- Inorder Traversal: \(O(n)\)
- Space Complexity: \(O(n)\)
