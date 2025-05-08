# -Maximum-Length-of-Pair-Chain

A Python solution to the *Maximum Length of Pair Chain* problem (LeetCode #646), implementing an efficient greedy algorithm.

## Problem Statement
Given `n` pairs of numbers `[a, b]`, find the maximum length of a chain where each consecutive pair `[c, d]` follows `[a, b]` if and only if `b < c`.

**Example:**
```python
Input: [[1,2], [2,3], [3,4]]
Output: 2

Greedy Algorithm
Sort pairs by their end values (b)

Iterate through pairs, selecting each valid pair (where current start > last end)

Track count of selected pairs and last end value

Time Complexity: O(n log n) (due to sorting)
Space Complexity: O(1
