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

You are given a simple connected undirected graph with \(N\) vertices and \(M\) edges. Each vertex \(i\) (\(1 \leq i \leq N\)) has a weight \(A_i\). Each edge \(j\) (\(1 \leq j \leq M\)) connects vertices \(U_j\) and \(V_j\) bidirectionally and has a weight \(B_j\).

The weight of a path in this graph is defined as the sum of the weights of the vertices and edges that appear on the path.

For each \(i = 2, 3, \ldots, N\), solve the following problem:
Find the minimum weight of a path from vertex 1 to vertex \(i\).

**Input:**

The input is given from Standard Input in the following format:
```
N M
A1 A2 ... AN
U1 V1 B1
U2 V2 B2
...
UM VM BM
```

**Output:**

Print the answers for \(i = 2, 3, \ldots, N\) in a single line, separated by spaces.

**Constraints:**

- \(2 \leq N \leq 2 \times 10^5\)
- \(N-1 \leq M \leq 2 \times 10^5\)
- \(1 \leq U_j < V_j \leq N\)
- \((U_i, V_i) \neq (U_j, V_j)\) if \(i \neq j\)
- The graph is connected
- \(0 \leq A_i \leq 10^9\)
- \(0 \leq B_j \leq 10^9\)
- All input values are integers.

**Example Input:**

```
3 3
1 2 3
1 2 1
1 3 6
2 3 2
```

**Example Output:**

```
4 9
```
