# Plus Minus

- Given an array of integers, calculate the ratios of its elements that are positive, negative, and zero. Print the decimal value of each fraction on a new line with  places after the decimal.

Note: This challenge introduces precision problems. The test cases are scaled to six decimal places, though answers with absolute error of up to  are acceptable.

## Constraints

- `0 < n ≤ 100`
- `-100 ≤ arr[i] ≤ 100`

## Print

Print the ratios of positive, negative and zero values in the array. Each value should be printed on a separate line with  digits after the decimal. The function should not return a value.

## Input Format

The first line contains an integer, , the size of the array.
The second line contains  space-separated integers that describe .

## Output Format

Print the following  lines, each to  decimals:

- proportion of positive values
- proportion of negative values
- proportion of zeros

### Example 1

  | STDIN      | Function |
  | ----------- | ----------- |
  | 6      | arr[] size n = 6|
  | -4 3 -9 0 4 1   | arr = [-4, 3, -9, 0, 4, 1]|

  ##### Sample Output:
  > 0.500000
    0.333333
    0.166667

  ##### Explanation:
  > There are 3 positive numbers, 2 negative numbers, and 1 zero in the array.
  The proportions of occurrence are positive: `3/6 = 0.5000000`, negative: `2/6 = 0.333333` and zeros: `1/6 = 0.166667`.

## Solution(s)

`Time Complexity:  O(n)`
