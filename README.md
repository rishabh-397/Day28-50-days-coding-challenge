# Day28-50-days-coding-challenge

Problem 1: Minimum Depth of a Binary Tree
- Find the shortest path from the root to a leaf.
- Approach: Breadth-first search (BFS) traversal or recursive DFS.
- Time Complexity: O(N), where N is the number of nodes.
- Handles empty trees and trees with single nodes.

Example:
Input: root = [3,9,20,null,null,15,7]

Output: 2

Problem 2: Subarrays with LCM Equal to K
- Count contiguous subarrays where the least common multiple (LCM) of elements equals k.
- Approach: Nested loops to check all subarrays; use gcd and lcm functions.
- Time Complexity: O(n^2 * log(max(nums))), due to lcm calculation for each subarray.
- Edge cases: arrays of length 1, k not in nums.

Example:
Input: nums = [3,6,2,7,1], k = 6

Output: 4

This solution is part of the #DrGViswanathanChallenge for 50 days of coding.

Stay tuned for the next day’s challenge!
