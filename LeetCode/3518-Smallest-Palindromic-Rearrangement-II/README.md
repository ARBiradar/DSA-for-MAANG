# 3518. Smallest Palindromic Rearrangement II

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
    return res

  def _nCk(self, n: int, k: int) -> int:
    res = 1
    for i in range(1, min(k, n - k) + 1):
      res = res * (n - i + 1) // i
      if res >= self.MAX:
        return self.MAX
    return res

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-29

---
*Auto-pushed by [CodePush Extension](https://github.com)*
