13. K Smallest Elements Using Partitioning
Question Description: Implement an algorithm to find the \(k\) smallest elements in an unsorted array using the partitioning technique of Quick Sort, commonly known as Quickselect. Partition the array around a pivot and continue only in the section that contains the required elements.

Test Cases:
- Test Case 1: Find the three smallest elements.
  - Input: Array: 7 10 4 3 20 15, \(k=3\)
  - Expected Output (sorted): 3 4 7
- Test Case 2: Find the two smallest elements.
  - Input: Array: 9 1 6 2 8, \(k=2\)
  - Expected Output (sorted): 1 2
Time Complexity:
- Best/Expected Case: \(O(n)\)
- Average/Expected Case: \(O(n)\) with randomized pivot selection
- Worst Case: \(O(n^2)\)
- Auxiliary Space Complexity: \(O(1)\) for iterative in-place partitioning, excluding output storage
