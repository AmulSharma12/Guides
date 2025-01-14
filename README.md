# Data Structures and Algorithms Pattern Guide

## Table of Contents
1. [Arrays and Strings](#arrays-and-strings)
2. [Two Pointers](#two-pointers)
3. [Sliding Window](#sliding-window)
4. [Binary Search](#binary-search)
5. [Hash Tables](#hash-tables)
6. [Linked Lists](#linked-lists)
7. [Trees and Graphs](#trees-and-graphs)
8. [Dynamic Programming](#dynamic-programming)
9. [Backtracking](#backtracking)
10. [Greedy Algorithms](#greedy-algorithms)

## Arrays and Strings

### Pattern: Prefix Sum
- **Description**: Calculate cumulative sum to optimize range queries
- **Similar Problems**:
  1. [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/)
  2. [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
  3. [Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/)

### Pattern: Kadane's Algorithm
- **Description**: Find maximum subarray sum
- **Similar Problems**:
  1. [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)
  2. [Maximum Sum Circular Subarray](https://leetcode.com/problems/maximum-sum-circular-subarray/)
  3. [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)

## Two Pointers

### Pattern: Opposite Direction
- **Description**: Two pointers moving from ends towards center
- **Similar Problems**:
  1. [Two Sum II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
  2. [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
  3. [Container With Most Water](https://leetcode.com/problems/container-with-most-water/)

### Pattern: Same Direction
- **Description**: Two pointers moving in same direction
- **Similar Problems**:
  1. [Remove Duplicates](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
  2. [Move Zeroes](https://leetcode.com/problems/move-zeroes/)
  3. [3Sum](https://leetcode.com/problems/3sum/)

## Sliding Window

### Pattern: Fixed Size Window
- **Description**: Window of fixed size k
- **Similar Problems**:
  1. [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/)
  2. [Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii/)
  3. [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)

### Pattern: Variable Size Window
- **Description**: Window size varies based on conditions
- **Similar Problems**:
  1. [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
  2. [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/)
  3. [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)

## Binary Search

### Pattern: Classic Binary Search
- **Description**: Search in sorted array
- **Similar Problems**:
  1. [Binary Search](https://leetcode.com/problems/binary-search/)
  2. [Search Insert Position](https://leetcode.com/problems/search-insert-position/)
  3. [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)

### Pattern: Binary Search on Answer
- **Description**: Use binary search to find optimal value
- **Similar Problems**:
  1. [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/)
  2. [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/)
  3. [Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/)

## Hash Tables

### Pattern: Frequency Counter
- **Description**: Count occurrences using hash map
- **Similar Problems**:
  1. [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
  2. [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
  3. [Group Anagrams](https://leetcode.com/problems/group-anagrams/)

### Pattern: Two Sum Pattern
- **Description**: Use hash table for complement finding
- **Similar Problems**:
  1. [Two Sum](https://leetcode.com/problems/two-sum/)
  2. [4Sum](https://leetcode.com/problems/4sum/)
  3. [Pairs of Songs](https://leetcode.com/problems/pairs-of-songs-with-total-durations-divisible-by-60/)

## Linked Lists

### Pattern: Fast & Slow Pointers
- **Description**: Detect cycles and find middle
- **Similar Problems**:
  1. [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)
  2. [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/)
  3. [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)

### Pattern: Reverse Linked List
- **Description**: In-place reversal of linked list
- **Similar Problems**:
  1. [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
  2. [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/)
  3. [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)

## Trees and Graphs

### Pattern: DFS (Depth-First Search)
- **Description**: Explore deep into structure first
- **Similar Problems**:
  1. [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
  2. [Course Schedule](https://leetcode.com/problems/course-schedule/)
  3. [Number of Islands](https://leetcode.com/problems/number-of-islands/)

### Pattern: BFS (Breadth-First Search)
- **Description**: Level by level traversal
- **Similar Problems**:
  1. [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
  2. [Word Ladder](https://leetcode.com/problems/word-ladder/)
  3. [Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/)

## Dynamic Programming

### Pattern: 1D Dynamic Programming
- **Description**: Linear state dependency
- **Similar Problems**:
  1. [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
  2. [House Robber](https://leetcode.com/problems/house-robber/)
  3. [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)

### Pattern: 2D Dynamic Programming
- **Description**: Matrix state dependency
- **Similar Problems**:
  1. [Unique Paths](https://leetcode.com/problems/unique-paths/)
  2. [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
  3. [Edit Distance](https://leetcode.com/problems/edit-distance/)

## Backtracking

### Pattern: Decision Making
- **Description**: Build solutions incrementally
- **Similar Problems**:
  1. [Subsets](https://leetcode.com/problems/subsets/)
  2. [Permutations](https://leetcode.com/problems/permutations/)
  3. [N-Queens](https://leetcode.com/problems/n-queens/)

### Pattern: String Building
- **Description**: Generate valid combinations
- **Similar Problems**:
  1. [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)
  2. [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
  3. [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)

## Greedy Algorithms

### Pattern: Interval Scheduling
- **Description**: Optimize interval selection
- **Similar Problems**:
  1. [Merge Intervals](https://leetcode.com/problems/merge-intervals/)
  2. [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)
  3. [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/)

### Pattern: Activity Selection
- **Description**: Choose optimal activities
- **Similar Problems**:
  1. [Jump Game](https://leetcode.com/problems/jump-game/)
  2. [Gas Station](https://leetcode.com/problems/gas-station/)
  3. [Task Scheduler](https://leetcode.com/problems/task-scheduler/)

## Additional Resources
- [LeetCode Patterns](https://seanprashad.com/leetcode-patterns/)
- [Blind 75 LeetCode Questions](https://leetcode.com/discuss/general-discussion/460599/blind-75-leetcode-questions)
- [Grind 75 Questions](https://www.techinterviewhandbook.org/grind75)
- [NeetCode 150](https://neetcode.io/)


More Problem Links
================================================ 
## Additional Resources

### Top 5 Learning Platforms
1. **AlgoExpert** - [algoexpert.io](https://algoexpert.io)
   - Curated list of 160+ problems
   - Video explanations for each solution
   - Space-time complexity analysis

2. **Grokking the Coding Interview** - [designgurus.org/course/grokking-the-coding-interview](https://designgurus.org/course/grokking-the-coding-interview)
   - Pattern-based learning approach
   - Comprehensive problem explanations
   - Interactive coding environment

3. **ByteByByte** - [byte-by-byte.com](https://byte-by-byte.com)
   - Focus on system design
   - Weekly coding problems
   - Interview preparation strategies

4. **InterviewCamp** - [interviewcamp.io](https://interviewcamp.io)
   - Systematic problem-solving approach
   - Live coding sessions
   - Pattern recognition training

5. **Back To Back SWE** - [youtube.com/c/BackToBackSWE](https://youtube.com/c/BackToBackSWE)
   - In-depth video explanations
   - Visual problem breakdowns
   - Advanced algorithm concepts

### Additional Practice Problems by Pattern

#### Arrays and Strings
- [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)
- [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
- [Next Permutation](https://leetcode.com/problems/next-permutation/)
- [Rotate Array](https://leetcode.com/problems/rotate-array/)
- [Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/)

#### Two Pointers
- [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)
- [Sort Colors](https://leetcode.com/problems/sort-colors/)
- [4Sum II](https://leetcode.com/problems/4sum-ii/)
- [Shortest Unsorted Continuous Subarray](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/)
- [Boats to Save People](https://leetcode.com/problems/boats-to-save-people/)

#### Sliding Window
- [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
- [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
- [Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/)
- [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/)
- [Permutation in String](https://leetcode.com/problems/permutation-in-string/)

#### Binary Search
- [Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/)
- [Find Peak Element](https://leetcode.com/problems/find-peak-element/)
- [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)
- [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)
- [Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)

#### Hash Tables
- [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)
- [First Missing Positive](https://leetcode.com/problems/first-missing-positive/)
- [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
- [Longest Palindrome by Concatenating Two Letter Words](https://leetcode.com/problems/longest-palindrome-by-concatenating-two-letter-words/)
- [Design Underground System](https://leetcode.com/problems/design-underground-system/)

#### Linked Lists
- [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/)
- [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
- [LRU Cache](https://leetcode.com/problems/lru-cache/)
- [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)
- [Sort List](https://leetcode.com/problems/sort-list/)

#### Trees and Graphs
- [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)
- [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)
- [All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/)
- [Word Search II](https://leetcode.com/problems/word-search-ii/)
- [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/)

#### Dynamic Programming
- [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/)
- [Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/)
- [Burst Balloons](https://leetcode.com/problems/burst-balloons/)
- [Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/)
- [Stone Game III](https://leetcode.com/problems/stone-game-iii/)

#### Backtracking
- [Word Search](https://leetcode.com/problems/word-search/)
- [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)
- [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/)
- [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/)
- [Word Pattern II](https://leetcode.com/problems/word-pattern-ii/)

#### Greedy Algorithms
- [Maximum Number of Events That Can Be Attended](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/)
- [Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)
- [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/)
- [Minimum Deletions to Make Character Frequencies Unique](https://leetcode.com/problems/minimum-deletions-to-make-character-frequencies-unique/)
- [Partition Labels](https://leetcode.com/problems/partition-labels/)

### Essential Problem Collections
- [Blind 75 LeetCode Questions](https://leetcode.com/discuss/general-discussion/460599/blind-75-leetcode-questions)
- [Grind 75 Questions](https://www.techinterviewhandbook.org/grind75)
- [NeetCode 150](https://neetcode.io/)
- [LeetCode Patterns](https://seanprashad.com/leetcode-patterns/)
- [14 Patterns to Ace Any Coding Interview Question](https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed)
