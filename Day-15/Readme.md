# Day 15

## Problem 1: Count Partitions with Even Sum Difference

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Calculate the total sum of the array. If the total sum is odd, no valid partition exists, so return `0`. Otherwise, every partition between adjacent elements satisfies the condition, so return `n - 1`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(1)**

---

## Problem 2: Plus One

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Traverse the digits array from right to left. If a digit is less than `9`, increment it and return the array. Otherwise, set it to `0` and continue. If all digits are `9`, create a new array with an extra leading `1`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(1)** *(O(n) only when a new array is created for all 9s)*
