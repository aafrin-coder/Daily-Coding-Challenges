# Day 09

## Problem 1

**Name:** 4Sum

- Platform: LeetCode
- Difficulty: Medium
- Language: Java
- Approach: Sort the array first. Fix the first two elements using nested loops, then use the two-pointer technique to find the remaining two elements whose sum equals the target. Skip duplicate values to avoid repeated quadruplets.
- Time Complexity: O(n³)
- Space Complexity: O(1) (excluding the output list)

---

## Problem 2

**Name:** Find Numbers with Even Number of Digits

- Platform: LeetCode
- Difficulty: Easy
- Language: Java
- Approach: Traverse each number in the array, count its digits by repeatedly dividing by 10, and check whether the digit count is even. Increment the counter for every number with an even number of digits.
- Time Complexity: O(n × d) (where d is the number of digits)
- Space Complexity: O(1)

---

## Summary

- Problems Solved: 2
- Easy: 1
- Medium: 1
