2. Doubly Linked List
Question Description: Implement a Doubly Linked List in which each node contains data, a pointer to the next node, and a pointer to the previous node. Support insertion at both ends, deletion, and traversal in forward and backward directions.

Test Cases:
- Test Case 1: Insert elements at the front and back.
  - Input Sequence: push_front(10), push_front(20), push_back(30), push_back(40)
  - Expected Output (forward): 20 10 30 40
  - Expected Output (backward): 40 30 10 20
- Test Case 2: Delete the last node.
  - Operation: pop_back()
  - Expected Output (forward): 20 10 30
Time Complexity:
- Insertion at front: \(O(1)\)
- Insertion at end with tail pointer: \(O(1)\)
- Deletion at front/end with head and tail pointers: \(O(1)\)
- Searching/Traversal: \(O(n)\)
