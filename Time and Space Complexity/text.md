**What is Time Complexity?**

>The time complexity, computational complexity, or temporal complexity describes the amount of time necessary to execute an algorithm. It is not a measure of the actual time taken to run an algorithm; instead, it is a measure of how the time taken scales with changes in the input length. As a result, the size and magnitude of the processed data have a significant impact. Moreover, it also aids in defining an algorithm's usefulness and evaluating its performance.


**What is Space Complexity?**

>The overall amount of memory or space utilized by an algorithm/program, including the space of input values for execution, is called space complexity. To determine space complexity, simply compute how much space the variables in an algorithm/a program take up.


**Understanding the common time and space complexities of various data structures and algorithms is essential for efficient problem-solving.**

**Time Complexities:**
'''
- Constant Time: O(1)
- Linear Time: O(n)
- Logarithmic Time: O(log n)
- Quadratic Time: O(n^2)
- Exponential Time: O(2^n)
'''

**Space Complexities:**
'''
- Constant Space: O(1)
- Linear Space: O(n)
- Quadratic Space: O(n^2)
- Exponential Space: O(2^n)
'''

**Examples of each common time complexity**
'''
O(n!) [Factorial time]: Permutations of 1 … n
O(2n) [Exponential time]: Exhaust all subsets of an array of size n
O(n3) [Cubic time]: Exhaust all triangles with side length less than n
O(n2) [Quadratic time]: Slow comparison-based sorting (e.g. Bubble Sort, Insertion Sort, Selection Sort)
O(n log n) [Linearithmic time]: Fast comparison-based sorting (e.g. Merge Sort)
O(n) [Linear time]: Linear Search (Finding maximum/minimum element in a 1D array), Counting Sort
O(log n) [Logarithmic time]: Binary Search, finding GCD (Greatest Common Divisor) using Euclidean Algorithm
O(1) [Constant time]: Calculation (e.g. Solving linear equations in one unknown)
'''

**Note:**

Observe that 1 ≤ n, c ≤ 109. Referring to the information above, the program’s time complexity should be either O(log n) or O(1). 
Since no O(1) solution exists, we conclude that binary search must be used.

In this problem, 1 ≤ n ≤ 105, which suggests that the time complexity can be either O(n log n) or O(n). It is quite obvious that sorting 
is required. Therefore, O(n log n) is the correct solution of this problem.Notice that n in very small (1 ≤ n ≤ 1000) in this problem. 
It means that a O(n2) solution can solve it. We simply need to simulate the robot’s moves.


**How to determine the solution of a problem by looking at its constraints?**

By looking at the constraints of a problem, we can often "guess" the solution.

Common time complexities

Let n be the main variable in the problem.

If n ≤ 12, the time complexity can be O(n!).
If n ≤ 25, the time complexity can be O(2n).
If n ≤ 100, the time complexity can be O(n4).
If n ≤ 500, the time complexity can be O(n3).
If n ≤ 104, the time complexity can be O(n2).
If n ≤ 106, the time complexity can be O(n log n).
If n ≤ 108, the time complexity can be O(n).
If n > 108, the time complexity can be O(log n) or O(1).\


