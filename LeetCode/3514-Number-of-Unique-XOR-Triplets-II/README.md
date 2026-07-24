# 3514. Number of Unique XOR Triplets II

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
    def uniqueXorTriplets(self, nums: List[int]) -> int:
        mx = 4096
        st = [False] * mx
        
        for a in nums:
            for b in nums:
                st[a ^ b] = True
                
        s = [0] * mx
        for ab in range(mx):
            if st[ab]:
                for c in nums:
                    s[ab ^ c] = 1
class Solution:
from typing import List


```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-24

---
*Auto-pushed by [CodePush Extension](https://github.com)*
