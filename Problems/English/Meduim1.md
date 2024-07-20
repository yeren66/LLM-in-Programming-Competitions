You are an expert C++ algorithm developer participating in a competitive programming contest. Your task is to solve challenging algorithmic problems efficiently and correctly. Follow these guidelines:

1. **Understand the Problem Statement:** Carefully read the problem statement and ensure you fully understand the requirements and constraints.
2. **Input and Output:** Pay close attention to the input and output specifications. Make sure your solution handles all edge cases.
3. **Optimal Solution:** Aim to provide an optimal solution in terms of time and space complexity.
4. **Code Quality:** Write clean, readable, and well-commented code. Use meaningful variable names and follow best practices for code formatting.
5. **Testing:** Include test cases to validate your solution. Cover a variety of cases including edge cases, large inputs, and typical scenarios.
6. **Efficiency:** Ensure your solution runs within the time limits and uses memory efficiently.
7. **Explanation:** Provide a clear and concise explanation of your approach and the reasoning behind your solution.

Below is the problem:

**Problem Statement:**

You are given \(N\) pairs of integers \((L_1, R_1), (L_2, R_2), \ldots, (L_N, R_N)\). Determine whether there exists a sequence of \(N\) integers \(X = (X_1, X_2, \ldots, X_N)\) that satisfies the following conditions, and print one such sequence if it exists:
1. \(L_i \leq X_i \leq R_i\) for each \(i = 1, 2, \ldots, N\).
2. The sum of \(X\) is 0.

**Input:**

The input is given from Standard Input in the following format:
```
N
L1 R1
L2 R2
...
LN RN
```

**Output:**

If multiple solutions exist, any of them will be considered correct.
If no solution exists, print `No`. Otherwise, print an integer sequence \(X\) that satisfies the conditions in the following format:
```
Yes
X1 X2 ... XN
```

**Constraints:**

- \(1 \leq N \leq 2 \times 10^5\)
- \(-10^9 \leq L_i \leq R_i \leq 10^9\)
- All input values are integers.

**Example Input:**

```
3
3 5
-4 1
-2 3
```

**Example Output:**

```
Yes
4 -3 -1
```
