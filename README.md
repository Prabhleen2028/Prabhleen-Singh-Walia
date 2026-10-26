15. Tower of Hanoi
Question Description: Implement the Tower of Hanoi problem using recursion. Move \(n\) disks from a source rod to a destination rod using an auxiliary rod, following these rules: only one disk can be moved at a time, only the top disk can be moved, and a larger disk cannot be placed on a smaller disk.

Test Cases:
- Test Case 1: Solve the problem for 3 disks.
  - Input: n = 3, Source: A, Auxiliary: B, Destination: C
  - Expected Output:
    1. Move disk 1 from A to C
    2. Move disk 2 from A to B
    3. Move disk 1 from C to B
    4. Move disk 3 from A to C
    5. Move disk 1 from B to A
    6. Move disk 2 from B to C
    7. Move disk 1 from A to C
  - Total Moves: 7
- Test Case 2: Solve the problem for 2 disks.
  - Input: n = 2
  - Expected Output: 3 moves
Time Complexity:
- Best Case: \(O(2^n)\)
- Average Case: \(O(2^n)\)
- Worst Case: \(O(2^n)\)
- Space Complexity: \(O(n)\) for the recursive call stack
- Minimum Number of Moves: \(2^n-1\)
