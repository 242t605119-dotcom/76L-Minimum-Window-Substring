# LeetCode 76 – Minimum Window Substring

Given two strings `s` and `t`, find the smallest substring of `s` that contains all the characters of `t`, including duplicate characters.

If no such substring exists, return an empty string.

## Example

### Input

```text
s = "ADOBECODEBANC"
t = "ABC"
```

### Output

```text
"BANC"
```

## Approach

I used the **Sliding Window** technique.

I keep two pointers, `left` and `right`, to represent the current window.

1. Expand the window using the `right` pointer.
2. Count the characters inside the window.
3. When the window contains all characters of `t`, try shrinking it from the left.
4. Keep track of the smallest valid window.
5. Continue until the complete string is checked.

## Complexity

* **Time Complexity:** `O(M + N)`
* **Space Complexity:** `O(M + N)`

## Language

**Python**

## LeetCode

**Problem:** 76. Minimum Window Substring
**Difficulty:** Hard
**Topic:** Hash Table, String, Sliding Window

## Author

T.Nandhini
