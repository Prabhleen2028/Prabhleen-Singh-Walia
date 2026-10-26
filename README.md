6. Binary Trees
Question Description: Implement a Binary Tree in which each node can have at most two children: a left child and a right child. Support node creation, insertion according to a defined strategy, and traversal operations such as preorder, inorder, and postorder.

Test Cases:

- Test Case 1: Create a binary tree with root 1, left child 2, and right child 3. Add 4 and 5 as children of node 2.
- Tree Structure:
  
Example binary tree

- Expected Preorder Output: 1 2 4 5 3
- Expected Inorder Output: 4 2 5 1 3
- Expected Postorder Output: 4 5 2 3 1
- Test Case 2: Traverse a tree containing only one node.
  - Input: Root: 10
  - Expected Output (all traversals): 10
Time Complexity:
- Insertion: Depends on the insertion strategy; \(O(n)\) for finding a position in a general tree
- Preorder Traversal: \(O(n)\)
- Inorder Traversal: \(O(n)\)
- Postorder Traversal: \(O(n)\)
- Searching: \(O(n)\)
- Space Complexity: \(O(n)\) for storing the tree; recursive traversal uses up to \(O(h)\) stack space, where \(h\) is the tree height
