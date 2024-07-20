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

You are given an integer sequence \(A\) of length \(N\) and integers \(K\) and \(X\). Print the integer sequence \(B\) obtained by inserting the integer \(X\) immediately after the \(K\)-th element of the sequence \(A\).

**Input:**

The input is given from Standard Input in the following format:
```
N K X
A1 A2 ... AN
```

**Output:**

Print the integer sequence \(B\) obtained by inserting the integer \(X\) immediately after the \(K\)-th element of the sequence \(A\), in the following format:
```
B1 B2 ... BN+1
```

**Constraints:**

- All input values are integers.
- \(1 \leq K \leq N \leq 100\)
- \(1 \leq A_i, X \leq 100\)

**Example Input:**

```
4 3 7
2 3 5 11
```

**Example Output:**

```
2 3 5 7 11
```