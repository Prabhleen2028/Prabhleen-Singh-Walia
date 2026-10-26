9. Quick Sort
Question Description: Implement Quick Sort to sort an array using a pivot element. Partition the array so that smaller elements are placed on one side of the pivot and larger elements on the other, then recursively sort both partitions.

Test Cases:
- Test Case 1: Sort an unsorted array.
  - Input: 10 7 8 9 1 5
  - Expected Output: 1 5 7 8 9 10
- Test Case 2: Sort an array in descending order.
  - Input: 9 7 5 3 1
  - Expected Output: 1 3 5 7 9
Time Complexity:
- Best Case: \(O(n\log n)\)
- Average Case: \(O(n\log n)\)
- Worst Case: \(O(n^2)\)
- Space Complexity: \(O(\log n)\) on average for recursive stack space; worst case \(O(n)\)
