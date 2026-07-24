# 3514. Number of Unique XOR Triplets II

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown

        k = 1 << max(V).bit_length()

        while V:
            v = V.pop()                         # pop :: prevents reuse below

            X3 |= {v ^ x2 for x2 in X2}         # existing pair ^ current 
            X2 |= {v ^ vv for vv in V}          # any value ^ current value => 
            
            if len(X3) == k: break
        
        return len(X3)

            value => triplet
            pair

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-24

---
*Auto-pushed by [CodePush Extension](https://github.com)*
