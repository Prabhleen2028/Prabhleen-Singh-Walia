12. Bucket Sort
Question Description: Implement Bucket Sort by distributing elements into several buckets according to their values. Sort each bucket individually and combine the buckets to obtain the final sorted array. For the example below, assume the input consists of numbers in the range \([0,1)\).

Test Cases:
- Test Case 1: Sort decimal values.
  - Input: 0.42 0.32 0.23 0.52 0.25 0.47 0.51
  - Expected Output: 0.23 0.25 0.32 0.42 0.47 0.51 0.52
- Test Case 2: Sort an array with repeated values.
  - Input: 0.5 0.2 0.5 0.1
  - Expected Output: 0.1 0.2 0.5 0.5
Time Complexity:
- Best Case: \(O(n+k)\)
- Average Case: \(O(n+k)\), under a suitable distribution and bucket arrangement
- Worst Case: \(O(n^2)\), if most elements fall into one bucket and the bucket sorting method is quadratic
- Space Complexity: \(O(n+k)\)
