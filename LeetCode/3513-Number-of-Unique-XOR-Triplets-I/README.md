# 3513. Number of Unique XOR Triplets I

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
  public int uniqueXorTriplets(int[] nums) {
    final int n = nums.length;
    if (n < 3)
      return n;
    final int x = (int) (Math.log(n) / Math.log(2));
    return 1 << (x + 1);
  }
}

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-23

---
*Auto-pushed by [CodePush Extension](https://github.com)*
