# Day 12

## Problem 1

**Name:** Intersection of Two Arrays

- Platform: LeetCode
- Difficulty: Easy
- Language: Java
- Approach: Use a HashSet to store all unique elements from the first array. Traverse the second array and add common elements to another HashSet to avoid duplicates. Finally, convert the set into an array and return it.
- Time Complexity: O(n + m)
- Space Complexity: O(n)

---

## Problem 2

**Name:** Third Maximum Number

- Platform: LeetCode
- Difficulty: Easy
- Language: Java
- Approach: Sort the array in ascending order. Traverse it from the end while counting distinct elements. Return the third distinct maximum if it exists; otherwise, return the maximum element.
- Time Complexity: O(n log n)
- Space Complexity: O(1)
