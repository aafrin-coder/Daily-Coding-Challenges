# Day 23

## Problem 1: Word Pattern

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Use a `HashMap` to map each character in the pattern to a unique word and a `HashSet` to ensure no two characters map to the same word. Traverse the pattern and corresponding words together. If a mapping already exists, verify it matches the current word. Otherwise, create a new mapping. If all mappings are consistent, return `true`; otherwise, return `false`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(n)**

---

## Problem 2: Reverse String

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Use the two-pointer technique. Initialize one pointer at the beginning and the other at the end of the character array. Swap the characters at both pointers, then move them toward each other until they meet. This reverses the string in-place.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(1)**
