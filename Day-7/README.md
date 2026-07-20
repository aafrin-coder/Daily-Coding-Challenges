# Day 07

## Problem 1

**Name:** Find First and Last Position of Element in Sorted Array

- Platform: LeetCode
- Difficulty: Medium
- Language: Java
- Approach: Traverse the array to find the target element. Once found, continue checking consecutive elements to determine the last occurrence and return the first and last indices. If the target is not present, return `[-1, -1]`.
- Time Complexity: O(n)
- Space Complexity: O(1)

---

## Problem 2

**Name:** Duplicate Emails

- Platform: LeetCode
- Difficulty: Easy
- Language: MySQL
- Approach: Group records by email and use the `HAVING` clause with `COUNT(email) > 1` to retrieve emails that appear more than once.
- Time Complexity: O(n)
- Space Complexity: O(1)

---

## Summary

- Problems Solved: 2
- Easy: 1
- Medium: 1
