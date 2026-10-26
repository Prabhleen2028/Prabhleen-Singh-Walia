19. Parenthesis Matching
Question Description: Implement a program to check whether parentheses and brackets in an expression are balanced using a Stack. Every opening bracket must have a corresponding closing bracket of the same type, and the brackets must close in the correct order. The program may support (), {}, and [].

Test Cases:
- Test Case 1: Check a balanced expression.
  - Input: {[()]}
  - Expected Output: Balanced
- Test Case 2: Check an unbalanced expression.
  - Input: {[(])}
  - Expected Output: Not Balanced
- Test Case 3: Check an expression with unmatched opening brackets.
  - Input: ((a+b)
  - Expected Output: Not Balanced
- Test Case 4: Check an expression with no brackets.
  - Input: a+b*c
  - Expected Output: Balanced
Time Complexity:
- Best Case: \(O(n)\) upper-bounded by the length of the expression
- Average Case: \(O(n)\)
- Worst Case: \(O(n)\)
- Space Complexity: \(O(n)\) in the worst case, when all characters are opening brackets
