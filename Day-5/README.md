# Day 05

## Problem 1

**Name:** Search Insert Position

- Platform: LeetCode
- Difficulty: Easy
- Language: Java
- Approach: Use Binary Search on the sorted array. Compare the target with the middle element and search the left or right half accordingly. If the target is not found, return the left pointer as the correct insertion index.
- Time Complexity: O(log n)
- Space Complexity: O(1)

---

## Problem 2

**Name:** Perfect Number

- Platform: LeetCode
- Difficulty: Easy
- Language: Java
- Approach: Iterate through all numbers from 1 to `num - 1`. Add every divisor of the given number to a sum. If the sum equals the original number, return `true`; otherwise, return `false`.
- Time Complexity: O(n)
- Space Complexity: O(1)

---

## Summary

- Problems Solved: 2
- Easy :2
