# Day 10

## Problem 1

**Name:** Running Sum of 1d Array

- Platform: LeetCode
- Difficulty: Easy
- Language: Java
- Approach: Traverse the array from the second element to the end. Update each element by adding the previous element's running sum, then return the modified array.
- Time Complexity: O(n)
- Space Complexity: O(1)

---

## Problem 2

**Name:** Biggest Single Number

- Platform: LeetCode
- Difficulty: Easy
- Language: MySQL
- Approach: Group the numbers by their value and select only those that appear exactly once using `HAVING COUNT(*) = 1`. Return the maximum among these unique numbers using the `MAX()` function.
- Time Complexity: O(n)
- Space Complexity: O(n)

---

## Summary

- Problems Solved: 2
- Easy: 2
