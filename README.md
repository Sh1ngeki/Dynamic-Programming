# Dynamic Programming Algorithms

## Overview
Collection of dynamic programming solutions solving three classic algorithmic challenges:
- Coin Change Problem
- Longest Increasing Subsequence
- Word Break Problem

## Problems

### 1. Coin Change
**Task**: Minimum coins to make a target amount
- Input: Coin denominations, target amount
- Returns minimum coins or -1 if impossible
- Assumes infinite coins of each type

### 2. Longest Increasing Subsequence
**Task**: Length of longest strictly increasing subsequence
- Input: Integer array
- Returns subsequence length
- O(n²) time complexity

### 3. Word Break
**Task**: Validate if string can be segmented using dictionary words
- Input: String, word dictionary
- Returns boolean if segmentation possible
- Allows word reuse

## Usage
```python
solution = Solution()
solution.coinChange([1, 2, 5], 11)  # Example
solution.lengthOfLIS([10,9,2,5,3,7,101,18])
solution.wordBreak("applepenapple", ["apple","pen"])
```

