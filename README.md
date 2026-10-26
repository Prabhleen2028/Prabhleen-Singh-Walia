11. Heap Sort
Question Description: Implement Heap Sort to arrange an array in ascending order using a Max Heap. First build the heap, then repeatedly move the maximum element to the end of the array and restore the heap property.

Test Cases:
- Test Case 1: Sort an unsorted array.
  - Input: 12 11 13 5 6 7
  - Expected Output: 5 6 7 11 12 13
- Test Case 2: Sort an array containing duplicate elements.
  - Input: 4 10 3 5 3
  - Expected Output: 3 3 4 5 10
Time Complexity:
- Building the heap: \(O(n)\)
- Best Case: \(O(n\log n)\)
- Average Case: \(O(n\log n)\)
- Worst Case: \(O(n\log n)\)
- Auxiliary Space Complexity: \(O(1)\) for an iterative in-place implementation
