## Description:
You are given an array containing n positive integers. Your task is to divide the array into k subarrays so that the maximum sum in a subarray is as small as possible. Explanation: An optimal division is [2,4], [7], [3,5] where the sums of the subarrays are 6, 7, 8. The largest sum is the last sum 8.

## Input
The first input line contains two integers n and k: the size of the array and the number of subarrays in the division. The next line contains n integers x1,x2,…,xn: the contents of the array.

## Output
Print one integer: the maximum sum in a subarray in the optimal division.
Constraints:
- 1 <= n <= 2 * 10^5
- 1 <= k <= n
- 1 <= xᵢ <= 10^9

## Example 
Input:
5 3  
2 4 7 3 5

Output:
8
