# Day 25

## Problem 1: Flip Binary Tree To Match Preorder Traversal

- **Platform:** LeetCode
- **Difficulty:** Medium
- **Language:** Java

### Approach
Use a recursive preorder traversal to match the given `voyage` array. Maintain an index to track the current position in the voyage. If the current node's value does not match the expected value, return `false`. If the left child exists and its value does not match the next expected value, flip the children by visiting the right subtree first and record the current node's value. Continue recursively until the entire preorder traversal matches the voyage. If the traversal cannot be matched, return `[-1]`.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(n)**

---

## Problem 2: Range Sum Query - Immutable

- **Platform:** LeetCode
- **Difficulty:** Easy
- **Language:** Java

### Approach
Use a **prefix sum array** to efficiently calculate the sum of elements between any given left and right indices. Create an array `pre` where `pre[i]` stores the sum of the first `i` elements. For a range from `left` to `right`, calculate the sum using `pre[right + 1] - pre[left]`. This allows each range-sum query to be answered in constant time.

### Time Complexity
- **O(n)** for preprocessing
- **O(1)** for each `sumRange` query

### Space Complexity
- **O(n)**
