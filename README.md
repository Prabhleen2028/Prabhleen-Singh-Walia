5. Queue Using Array
Question Description: Implement a linear Queue using an array supporting enqueue, dequeue, front, and display operations. The queue follows FIFO (First In, First Out). In a simple linear array implementation, deleted positions may not be reused without shifting or resetting the queue.

Test Cases:
- Test Case 1: Insert elements into the queue.
  - Input Sequence: enqueue(10), enqueue(20), enqueue(30)
  - Expected Output: 10 20 30
- Test Case 2: Remove the front element.
  - Operation: dequeue()
  - Expected Output: Dequeued: 10; remaining queue: 20 30
Time Complexity:
- Enqueue: \(O(1)\), when space is available
- Dequeue: \(O(1)\), when using front/rear indices without shifting
- Front: \(O(1)\)
- Display: \(O(n)\)
- Space Complexity: \(O(n)\)
