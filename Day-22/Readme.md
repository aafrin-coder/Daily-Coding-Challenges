# Day 22

## Problem 1: Largest Perimeter Triangle

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Sort the array in ascending order. Traverse from the largest side toward the beginning. For every three consecutive sides, check if the sum of the two smaller sides is greater than the largest side (`a + b > c`). If true, return their sum as the largest possible perimeter. If no valid triangle exists, return `0`.

### Time Complexity
- **O(n log n)** *(Sorting the array)*

### Space Complexity
- **O(1)** *(Ignoring sorting space used by Java)*

---

## Problem 2: Sort Array By Parity

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Create a new result array. Traverse the given array once. Place even numbers from the beginning of the result array and odd numbers from the end. Return the resulting array with all even elements before odd elements.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(n)**
