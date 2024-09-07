Writing a clear and effective prompt for solving a programming problem involves providing all relevant details in a structured manner. This helps ensure that the solution is accurate and tailored to your needs. Here's a guide on how to craft a well-defined prompt:

### Components of a Good Prompt

1. **Problem Statement:**
   - **Description:** Clearly describe the problem you are trying to solve. Include any specific constraints or requirements.
   - **Objective:** State what you need to achieve with the solution. For example, "Find the shortest path in a weighted graph" or "Compute the minimum cost to reach each platform."

2. **Input and Output:**
   - **Input Format:** Describe how the input is provided. Include details like the number of test cases, size of input arrays, etc.
   - **Output Format:** Specify the expected output format. For instance, "Return an array of integers" or "Print the results in a specific order."

3. **Constraints:**
   - **Limits:** Provide any constraints or limits on the input size, value ranges, time, and space complexity.
   - **Edge Cases:** Mention any edge cases or special conditions that need to be handled.

4. **Examples:**
   - **Sample Input/Output:** Provide one or more examples with corresponding input and expected output. Explain why the expected output is correct.
   - **Explanation:** Briefly explain the reasoning behind the example outputs if necessary.

5. **Function Signature (if applicable):**
   - **Function Definition:** Specify the function signature including the names and types of parameters. For example: `vector<long long> jumpGame(int N, vector<int>& d, vector<int>& c)`.

### Example Prompt

Here’s how you might structure a prompt based on the problem you provided:

---

**Problem Statement:**

You are given a list of platforms where each platform has a specific jump distance and a cost associated with jumping from that platform. You start at the last platform (index `N-1`) and can jump either forward or backward based on the given distances. Your task is to compute the minimum cost required to reach each platform from the starting platform. If a platform is not reachable, return `-1` for that platform.

**Input Format:**

- An integer `N`, the number of platforms.
- A vector `d` of size `N`, where `d[i]` represents the distance you can jump from platform `i`.
- A vector `c` of size `N`, where `c[i]` represents the cost of jumping from platform `i`.

**Output Format:**

- A vector of size `N`, where each element represents the minimum cost to reach that platform from the starting platform. If a platform is unreachable, the corresponding value should be `-1`.

**Constraints:**

- `1 <= N <= 100000`
- `1 <= d[i] <= N`
- `1 <= c[i] <= 1000`

**Examples:**

1. **Input:**
   ```
   4
   1 1 1 1
   10 5 2 4
   ```

   **Output:**
   ```
   17 7 2 0
   ```

   **Explanation:**
   - Starting from platform 3, you can jump forward to platform 2 at a cost of 4, then to platform 1 at a cost of 2, and finally to platform 0 at a cost of 7. The total cost to reach platform 0 is 17.

2. **Input:**
   ```
   5
   2 1 1 1 2
   3 2 1 4 5
   ```

   **Output:**
   ```
   3 2 1 4 5
   ```

   **Explanation:**
   - Each platform can be reached with the cost provided since the distances allow direct access to other platforms or are within the reachable bounds.

**Function Signature:**

```cpp
vector<long long> jumpGame(int N, vector<int>& d, vector<int>& c);
```

---

### Tips for Writing Effective Prompts

1. **Be Specific:** Provide as many details as possible to avoid ambiguity.
2. **Use Examples:** Concrete examples help clarify the problem and expected output.
3. **Specify Constraints:** Define limits and constraints to guide the solution towards efficiency.
4. **Define the Objective:** Clearly state what needs to be achieved with the solution.

By structuring your prompt with these components, you make it easier for others to understand the problem and provide accurate and efficient solutions.
