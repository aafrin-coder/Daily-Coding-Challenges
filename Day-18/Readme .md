# Problem 1

# Reverse Bits

- **Difficulty:** Easy
- **Language:** Java

## Approach
- Traverse all 32 bits.
- Shift the result left, add the last bit of `n`, and right-shift `n`.

## Complexity
- **Time:** O(1)
- **Space:** O(1)


# Problem 2

# Number of 1 Bits

- **Difficulty:** Easy
- **Language:** Java

## Approach
- Use Brian Kernighan’s algorithm.
- Repeatedly remove the lowest set bit until the number becomes 0.

## Complexity
- **Time:** O(k), where `k` is the number of set bits.
- **Space:** O(1)
