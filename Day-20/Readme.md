# Day 20

## Problem 1: Contains Duplicate

- **Platform:** Leet code
- **Difficulty:** Easy
- **Language:** Java

### Approach
Sort the given array. Traverse the sorted array and compare each element with its previous element. If any two adjacent elements are equal, return `true` because a duplicate exists. If no duplicates are found after the traversal, return `false`.

### Time Complexity
- **O(n log n)**

### Space Complexity
- **O(1)**

---

## Problem 2: Distribute Candies

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Use a `HashSet` to store all unique candy types. The sister can eat only half of the total candies (`n/2`). The maximum number of different candy types she can eat is the minimum of the number of unique candy types and `n/2`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(n)**
