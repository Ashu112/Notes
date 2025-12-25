# Subarray vs Subsequence vs Subset vs Permutation

These are general terms which are used in array and string questions and holds greater meaning to how a problem will be solved.

# SubArray
- Contigous 
- Order matters
- start index and end index matters
- count = n(n+1)/2
  
# Patterns to think if SubArray is asked
- Sliding Window
- Kadane's Algorithm
- Prefix Sum
- Maximum / Minimum Sum

# SubSequence
- Non Contigous
- Order Matters
- Count = 2^n

# Patterns to think if SubSequence is asked
- DP problem
- LIS(Longest Increasing Subsequence)
- String(LCS)

# Subset
- Non contigous
- Order does not matter
- Count = 2^n

# Patterns to think if SubSequence is asked
- Bit Masking
- Knapsack
- Combination Problem

# Permutation
- Order matters
- Count = n!

| Term        | Contiguous | Order Matters | Rearrangement Allowed | Count    |
| ----------- | ---------- | ------------- | --------------------- | -------- |
| Subarray    | ✅          | ✅             | ❌                     | n(n+1)/2 |
| Substring   | ✅          | ✅             | ❌                     | n(n+1)/2 |
| Subsequence | ❌          | ✅             | ❌                     | 2ⁿ       |
| Subset      | ❌          | ❌             | ❌                     | 2ⁿ       |
| Permutation | ❌          | ✅             | ✅                     | n!       |
