# Longest Increasing Continuous Subsequence
## Example
Give an integer array，find the longest increasing continuous subsequence in this array.

An increasing continuous subsequence:
- Can be from right to left or from left to right.
- Indices of the integers in the subsequence should be continuous.

For `[5, 4, 2, 1, 3]`, the LICS is `[5, 4, 2, 1]`, return 4.

For `[5, 1, 2, 3, 4]`, the LICS is `[1, 2, 3, 4]`, return 4.

## Solution
- Loop from left to right and then right to left
- Reset temperary length every time the trending is different
