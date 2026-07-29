# Day 16

## Problem 1: House Robber

- **Platform:** LeetCode
- **Difficulty:** Medium
- **Language:** Java

### Approach
Use Dynamic Programming with two variables to track the maximum money when robbing or skipping the current house. For each house, calculate the new robbed and not robbed values, then update them. The final answer is the maximum of the two.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(1)**

---

## Problem 2: Power of Two

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
If the number is `0`, return `false`. Repeatedly divide the number by `2` while it is even. If it becomes `1`, it is a power of two; otherwise, return `false`.

### Time Complexity
- **O(log n)**

### Space Complexity
- **O(1)**
