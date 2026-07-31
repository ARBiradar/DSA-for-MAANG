# 3016. Minimum Number of Pushes to Type Word II

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown

    for (final char c : word.toCharArray())
      ++count[c - 'a'];


    Arrays.sort(count);
    for (int i = 0; i < 26; ++i)
      ans += count[26 - i - 1] * (i / 8 + 1);
    int[] count = new int[26];
    int ans = 0;
  public int minimumPushes(String word) {
  // Same as 3014. Minimum Number of Pushes to Type Word I
class Solution {

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-31

---
*Auto-pushed by [CodePush Extension](https://github.com)*
