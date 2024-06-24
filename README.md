# Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit

LeetCode Q # 1438.

Given an array of integers nums and an integer limit, return the size of the longest non-empty subarray such that the absolute difference between any two elements of this subarray is less than or equal to limit.

Example 1:

>Input: nums = [8,2,4,7], limit = 4</br>
>Output: 2 </br>
>Explanation: All subarrays are: </br>
>[8] with maximum absolute diff |8-8| = 0 <= 4.</br>
>[8,2] with maximum absolute diff |8-2| = 6 > 4. </br>
>[8,2,4] with maximum absolute diff |8-2| = 6 > 4.</br>
>[8,2,4,7] with maximum absolute diff |8-2| = 6 > 4.</br>
>[2] with maximum absolute diff |2-2| = 0 <= 4.</br>
>[2,4] with maximum absolute diff |2-4| = 2 <= 4.</br>
>[2,4,7] with maximum absolute diff |2-7| = 5 > 4.</br>
>[4] with maximum absolute diff |4-4| = 0 <= 4.</br>
>[4,7] with maximum absolute diff |4-7| = 3 <= 4.</br>
>[7] with maximum absolute diff |7-7| = 0 <= 4. </br>
>Therefore, the size of the longest subarray is 2.</br>

Example 2:

>Input: nums = [10,1,2,4,7,2], limit = 5</br>
>Output: 4 </br>
>Explanation: The subarray [2,4,7,2] is the longest since the maximum absolute diff is |2-7| = 5 <= 5.

Example 3:

>Input: nums = [4,2,2,2,4,4,2,2], limit = 0</br>
>Output: 3

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Longest-Continuous-Subarray-With-Absolute-Diff-Less-Than-or-Equal-to-Limit-LeetCode/assets/171427226/e5900195-687c-43cd-aba6-eb49842e521f)

  Time complexity: O(n).</br>Space complexity: O(n).
</div>
