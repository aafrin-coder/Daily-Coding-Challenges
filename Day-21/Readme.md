# Day 21

## Problem 1: Maximum Subarray

- **Platform:** LeetCode
- **Difficulty:** Medium
- **Language:** Java

### Approach
Use **Kadane's Algorithm**. Initialize both the current sum and maximum sum with the first element. Traverse the array, updating the current sum as the maximum of the current element or the current sum plus the current element. Update the maximum sum whenever a larger sum is found.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(1)**

---

## Problem 2: Contains Duplicate II

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Use a **HashSet** as a sliding window of size `k`. Traverse the array and check whether the current element already exists in the set. If it does, return `true`. Otherwise, add it to the set. If the window size exceeds `k`, remove the element that is no longer in the window. If no duplicate is found, return `false`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(k)**
