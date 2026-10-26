6. Circular Queue Using Array
Question Description: Implement a Circular Queue using an array where the last position connects logically to the first position. Use modular arithmetic to reuse empty positions. Support enqueue, dequeue, front, and display operations.

Test Cases:
- Test Case 1: Insert elements into a queue of capacity 5.
  - Input Sequence: enqueue(10), enqueue(20), enqueue(30), enqueue(40)
  - Expected Output: 10 20 30 40
- Test Case 2: Delete two elements and insert two more.
  - Input Sequence: dequeue(), dequeue(), enqueue(50), enqueue(60)
  - Expected Output: 30 40 50 60
Time Complexity:
- Enqueue: \(O(1)\)
- Dequeue: \(O(1)\)
- Front: \(O(1)\)
- Display: \(O(n)\)
- Space Complexity: \(O(n)\)
