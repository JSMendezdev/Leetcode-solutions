/* Leetcode-solutions
leetcode solutions from my CSC 220 Algorithms course
--
Sort Colors (Leetcode problem 75)

Problem 
Sort an array containing only 0s, 1s, and 2s in-place

Approach
Usec Counting Sort
-Count occurrences of each value (0,1,2)
-Compute prefix sums
-O(n) time complexity

Key Concepts
-Counting Sort
-Stable sorting
-O(n) time complexity

--
Maximum Gap (Leetcode problem 164)

Problem 
Find the maximum difference between consecutive elements in sorted order without actually sorting the array

Approach
Used Bucket Sort
-Compute min and max
-Divide range into buckets
-Store only min and max per bucket
-Maximum gap occurs between buckets, not inside

Key concepts
-Bucket Sort
-Min/Max tracking
-Linear time optimization

--
Partition Equal Subset Sum (Leetcode problem 416)

Approach
Dynamic Programming (Subset Sum) : We check whether the array can be split into two subsets with equal sum by reducing the problem to finding a subset that sums to total/2

Key concepts
-Transform problem into subset sum
-Use DP to track achievable sum

Time complexity
O(n * sum)
