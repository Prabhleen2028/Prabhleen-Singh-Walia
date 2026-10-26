1. Singly Linked List
Question Description: Implement a Singly Linked List class or structure supporting fundamental operations such as insertion at the beginning (push_front), insertion at the end (push_back), deletion of nodes, and traversal/printing of elements.

Test Cases:
- Test Case 1: Insert elements 1, 2 at the front and 3, 4 at the back.
  - Input Sequence: push_front(1), push_front(2), push_back(3), push_back(4)
  - Expected Output: 2 1 3 4
- Test Case 2: Delete from the back after insertions.
  - Operation: pop_back()
  - Expected Output: 2 1 3
Time Complexity:
- Insertion at front (push_front): \(O(1)\)
- Insertion at end (push_back) with tail pointer: \(O(1)\); without tail pointer: \(O(n)\)
- Deletion from end (pop_back): \(O(n)\)
- Traversal/Search: \(O(n)\)
