# Day 24

## Problem 1: N-th Tribonacci Number

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Use an iterative approach with three variables to store the previous three Tribonacci numbers. The Tribonacci sequence is defined as `T(n) = T(n-1) + T(n-2) + T(n-3)`, with `T(0) = 0`, `T(1) = 1`, and `T(2) = 1`. Handle the base cases first, then calculate each subsequent value using a loop until reaching `n`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(1)**

---

## Problem 2: Summary Ranges

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Traverse the sorted array and identify consecutive ranges. Keep track of the starting value of each range. When the consecutive sequence ends, add either a single number or a range in the required format. Continue this process until all elements are processed.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(n)**
