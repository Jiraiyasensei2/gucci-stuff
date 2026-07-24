# EPAM Coding Sheet — AI-Native SWE Intern Prep

Based on the actual JD: this role screens for **solid fundamentals in one language + basic OOP/DS understanding**, not competitive-programming depth. So this sheet is weighted toward core patterns done cleanly, rather than obscure hard problems.

---

## Tier 1 — Must be flawless (Arrays, Strings, Hashing)
- [✔] Two Sum
- [Do] Best Time to Buy and Sell Stock
- [✔] Contains Duplicate
- [✔] Valid Anagram
- [✔] Group Anagrams
- [Do] Top K Frequent Elements
- [✔] Product of Array Except Self
- [✔] Valid Palindrome
- [✔] Longest Substring Without Repeating Characters
- [Do] Longest Repeating Character Replacement
- [✔] Remove Duplicates from Sorted Array (in-place, two pointers)
- [✔] 3Sum

## Tier 2 — Trees & BSTs (frequently reported in EPAM rounds)
- [✔] Invert Binary Tree
- [✔] Maximum Depth of Binary Tree
- [✔] Same Tree
- [ ] Validate Binary Search Tree
- [ ] Insert into a Binary Search Tree
- [ ] Lowest Common Ancestor of a BST
- [ ] Binary Tree Level Order Traversal
- [ ] Kth Smallest Element in a BST
- [ ] Construct Binary Tree from Preorder and Inorder Traversal

## Tier 3 — Linked Lists
- [ ] Reverse Linked List
- [ ] Merge Two Sorted Lists
- [ ] Linked List Cycle (Floyd's)
- [ ] Reorder List
- [ ] Remove Nth Node From End of List

## Tier 4 — Graphs / BFS-DFS (Number of Islands & Word Ladder specifically reported)
- [ ] Number of Islands
- [ ] Clone Graph
- [ ] Word Ladder
- [ ] Course Schedule (topological sort / cycle detection)
- [ ] Pacific Atlantic Water Flow

## Tier 5 — Dynamic Programming
- [ ] Climbing Stairs
- [ ] House Robber
- [ ] Coin Change
- [ ] Longest Increasing Subsequence
- [ ] Unique Paths
- [ ] 0/1 Knapsack (classic, not always on LeetCode by this name)

## Tier 6 — Stacks/Queues (lower frequency, quick to cover)
- [ ] Valid Parentheses
- [ ] Min Stack
- [ ] Implement Queue using Stacks

---

## Beyond raw DSA — what this JD specifically adds
This role explicitly tests **first-principles thinking**, not just "does the code pass." For every problem above, practice explaining out loud:
1. Why this approach (not just what it is)
2. Time/space complexity, and what you'd trade off for a different constraint
3. What would break it (edge cases) and how you'd verify

Also worth doing given the JD's OOP requirement: implement 2–3 of the classic **design patterns** (Singleton, Factory, Observer) from scratch in your primary language, since "basic OOP understanding" is explicitly named as a bar, not DSA alone.

---

## Suggested pacing (before the online assessment)
- Week 1: Tier 1 fully + start Tier 2
- Week 2: Finish Tier 2 + Tier 3
- Week 3: Tier 4 + Tier 5
- Week 4: Tier 6 + mixed timed mocks, explaining approach out loud each time
# EPAM LeetCode Problems Grouped by Topic

## Array (20)

- [ ] [3Sum](https://leetcode.com/problems/3sum) — Medium
- [ ] [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock) — Easy
- [ ] [First Missing Positive](https://leetcode.com/problems/first-missing-positive) — Hard
- [ ] [Group Anagrams](https://leetcode.com/problems/group-anagrams) — Medium
- [ ] [House Robber](https://leetcode.com/problems/house-robber) — Medium
- [ ] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array) — Medium
- [ ] [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix) — Easy
- [ ] [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence) — Medium
- [ ] [Maximum Subarray](https://leetcode.com/problems/maximum-subarray) — Medium
- [ ] [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays) — Hard
- [ ] [Merge Intervals](https://leetcode.com/problems/merge-intervals) — Medium
- [ ] [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array) — Easy
- [ ] [Minimum Operations to Make a Uni-Value Grid](https://leetcode.com/problems/minimum-operations-to-make-a-uni-value-grid) — Medium
- [ ] [Move Zeroes](https://leetcode.com/problems/move-zeroes) — Easy
- [ ] [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum) — Medium
- [ ] [Rotate Array](https://leetcode.com/problems/rotate-array) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium
- [ ] [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water) — Hard
- [ ] [Two Sum](https://leetcode.com/problems/two-sum) — Easy
- [ ] [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) — Medium

## String (16)

- [ ] [Edit Distance](https://leetcode.com/problems/edit-distance) — Medium
- [ ] [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string) — Easy
- [ ] [Generate Parentheses](https://leetcode.com/problems/generate-parentheses) — Medium
- [ ] [Group Anagrams](https://leetcode.com/problems/group-anagrams) — Medium
- [ ] [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix) — Easy
- [ ] [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring) — Medium
- [ ] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters) — Medium
- [ ] [Multiply Strings](https://leetcode.com/problems/multiply-strings) — Medium
- [ ] [Reverse String](https://leetcode.com/problems/reverse-string) — Easy
- [ ] [Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string) — Easy
- [ ] [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string) — Medium
- [ ] [Roman to Integer](https://leetcode.com/problems/roman-to-integer) — Easy
- [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency) — Medium
- [ ] [String Compression](https://leetcode.com/problems/string-compression) — Medium
- [ ] [Valid Anagram](https://leetcode.com/problems/valid-anagram) — Easy
- [ ] [Valid Parentheses](https://leetcode.com/problems/valid-parentheses) — Easy

## Hash Table (11)

- [ ] [First Missing Positive](https://leetcode.com/problems/first-missing-positive) — Hard
- [ ] [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string) — Easy
- [ ] [Group Anagrams](https://leetcode.com/problems/group-anagrams) — Medium
- [ ] [LRU Cache](https://leetcode.com/problems/lru-cache) — Medium
- [ ] [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence) — Medium
- [ ] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters) — Medium
- [ ] [Roman to Integer](https://leetcode.com/problems/roman-to-integer) — Easy
- [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium
- [ ] [Two Sum](https://leetcode.com/problems/two-sum) — Easy
- [ ] [Valid Anagram](https://leetcode.com/problems/valid-anagram) — Easy

## Two Pointers (11)

- [ ] [3Sum](https://leetcode.com/problems/3sum) — Medium
- [ ] [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring) — Medium
- [ ] [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array) — Easy
- [ ] [Move Zeroes](https://leetcode.com/problems/move-zeroes) — Easy
- [ ] [Reverse String](https://leetcode.com/problems/reverse-string) — Easy
- [ ] [Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string) — Easy
- [ ] [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string) — Medium
- [ ] [Rotate Array](https://leetcode.com/problems/rotate-array) — Medium
- [ ] [String Compression](https://leetcode.com/problems/string-compression) — Medium
- [ ] [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water) — Hard
- [ ] [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) — Medium

## Dynamic Programming (9)

- [ ] [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock) — Easy
- [ ] [Edit Distance](https://leetcode.com/problems/edit-distance) — Medium
- [ ] [Generate Parentheses](https://leetcode.com/problems/generate-parentheses) — Medium
- [ ] [House Robber](https://leetcode.com/problems/house-robber) — Medium
- [ ] [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring) — Medium
- [ ] [Maximum Subarray](https://leetcode.com/problems/maximum-subarray) — Medium
- [ ] [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum) — Medium
- [ ] [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water) — Hard
- [ ] [Unique Paths](https://leetcode.com/problems/unique-paths) — Medium

## Math (9)

- [ ] [Add Two Numbers](https://leetcode.com/problems/add-two-numbers) — Medium
- [ ] [Minimum Operations to Make a Uni-Value Grid](https://leetcode.com/problems/minimum-operations-to-make-a-uni-value-grid) — Medium
- [ ] [Multiply Strings](https://leetcode.com/problems/multiply-strings) — Medium
- [ ] [Palindrome Number](https://leetcode.com/problems/palindrome-number) — Easy
- [ ] [Pow(x, n)](https://leetcode.com/problems/powx-n) — Medium
- [ ] [Reverse Integer](https://leetcode.com/problems/reverse-integer) — Medium
- [ ] [Roman to Integer](https://leetcode.com/problems/roman-to-integer) — Easy
- [ ] [Rotate Array](https://leetcode.com/problems/rotate-array) — Medium
- [ ] [Unique Paths](https://leetcode.com/problems/unique-paths) — Medium

## Sorting (9)

- [ ] [3Sum](https://leetcode.com/problems/3sum) — Medium
- [ ] [Group Anagrams](https://leetcode.com/problems/group-anagrams) — Medium
- [ ] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array) — Medium
- [ ] [Merge Intervals](https://leetcode.com/problems/merge-intervals) — Medium
- [ ] [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array) — Easy
- [ ] [Minimum Operations to Make a Uni-Value Grid](https://leetcode.com/problems/minimum-operations-to-make-a-uni-value-grid) — Medium
- [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium
- [ ] [Valid Anagram](https://leetcode.com/problems/valid-anagram) — Easy

## Divide and Conquer (4)

- [ ] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array) — Medium
- [ ] [Maximum Subarray](https://leetcode.com/problems/maximum-subarray) — Medium
- [ ] [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays) — Hard
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium

## Linked List (4)

- [ ] [Add Two Numbers](https://leetcode.com/problems/add-two-numbers) — Medium
- [ ] [LRU Cache](https://leetcode.com/problems/lru-cache) — Medium
- [ ] [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists) — Easy
- [ ] [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list) — Easy

## Recursion (4)

- [ ] [Add Two Numbers](https://leetcode.com/problems/add-two-numbers) — Medium
- [ ] [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists) — Easy
- [ ] [Pow(x, n)](https://leetcode.com/problems/powx-n) — Medium
- [ ] [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list) — Easy

## Counting (3)

- [ ] [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string) — Easy
- [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium

## Heap (Priority Queue) (3)

- [ ] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array) — Medium
- [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium

## Binary Search (2)

- [ ] [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays) — Hard
- [ ] [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) — Medium

## Bucket Sort (2)

- [ ] [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium

## Database (2)

- [ ] [Count Salary Categories](https://leetcode.com/problems/count-salary-categories) — Medium
- [ ] [Duplicate Emails](https://leetcode.com/problems/duplicate-emails) — Easy

## Quickselect (2)

- [ ] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array) — Medium
- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements) — Medium

## Stack (2)

- [ ] [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water) — Hard
- [ ] [Valid Parentheses](https://leetcode.com/problems/valid-parentheses) — Easy

##  (1)

- [ ] [Counter](https://leetcode.com/problems/counter) — Easy

## Backtracking (1)

- [ ] [Generate Parentheses](https://leetcode.com/problems/generate-parentheses) — Medium

## Binary Tree (1)

- [ ] [Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor) — Medium

## Combinatorics (1)

- [ ] [Unique Paths](https://leetcode.com/problems/unique-paths) — Medium

## Depth-First Search (1)

- [ ] [Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor) — Medium

## Design (1)

- [ ] [LRU Cache](https://leetcode.com/problems/lru-cache) — Medium

## Doubly-Linked List (1)

- [ ] [LRU Cache](https://leetcode.com/problems/lru-cache) — Medium

## Matrix (1)

- [ ] [Minimum Operations to Make a Uni-Value Grid](https://leetcode.com/problems/minimum-operations-to-make-a-uni-value-grid) — Medium

## Monotonic Stack (1)

- [ ] [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water) — Hard

## Queue (1)

- [ ] [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string) — Easy

## Simulation (1)

- [ ] [Multiply Strings](https://leetcode.com/problems/multiply-strings) — Medium

## Sliding Window (1)

- [ ] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters) — Medium

## Tree (1)

- [ ] [Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor) — Medium

## Trie (1)

- [ ] [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix) — Easy

## Union-Find (1)

- [ ] [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence) — Medium
