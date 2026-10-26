14. Bin Sort
Question Description: Implement Bin Sort by distributing elements into bins based on their values or digit positions. Place elements into the appropriate bins and collect them in order. For this example, use non-negative integers from 0 to 9 as direct bin indices.

Test Cases:
- Test Case 1: Sort single-digit integers.
  - Input: 4 2 7 1 9 3
  - Expected Output: 1 2 3 4 7 9
- Test Case 2: Sort integers with repeated values.
  - Input: 5 2 5 1 2 3
  - Expected Output: 1 2 2 3 5 5
Time Complexity:
- Best Case: \(O(n+k)\)
- Average Case: \(O(n+k)\), for direct-index bins or an appropriate distribution
- Worst Case: Depends on the bin arrangement and the method used to handle collisions or sort individual bins
- Space Complexity: \(O(n+k)\)
Here, \(n\) is the number of elements and \(k\) is the number of bins. In this example, \(k=10\).

Note: Bin Sort is a distribution-based sorting approach. Its complexity depends on the value range and how elements are assigned to bins.
