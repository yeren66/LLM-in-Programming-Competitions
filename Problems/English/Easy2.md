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

Takahashi came to a store to buy a pen. Here, a red pen costs \(R\) yen, a green pen costs \(G\) yen, and a blue pen costs \(B\) yen.

Takahashi dislikes the color \(C\). If \(C\) is Red, he cannot buy a red pen; if \(C\) is Green, he cannot buy a green pen; and if \(C\) is Blue, he cannot buy a blue pen.

Determine the minimum amount of money he needs to buy one pen.

**Input:**

The input is given from Standard Input in the following format:
```
R 
G 
B
C
```

**Output:**

If the minimum amount of money Takahashi needs to buy one pen is \(X\) yen, print \(X\).

**Constraints:**

- \(1 \leq R, G, B \leq 100\)
- \(R\), \(G\), and \(B\) are integers.
- \(C\) is Red, Green, or Blue.

**Example Input 1:**

```
20 30 10
Blue
```

**Example Output 1:**

```
20
```
A red pen costs 20 yen, a green pen costs 30 yen, and a blue pen costs 10 yen. Takahashi cannot buy a blue pen, but he can buy a red pen for 20 yen.
