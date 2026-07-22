# 3501. Maximize Active Section with Trade II

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
    for (int[] query : queries) {
      final int l = query[0];
      final int r = query[1];
      final int left = zeroGroupIndex[l] == -1 ? -1
                                               : (zeroGroups.get
                                               (zeroGroupIndex[l]).
                                               length -
                                                  (l - zeroGroups.get
                                                  (zeroGroupIndex[l]).
                                                  start));
      final int right =
          zeroGroupIndex[r] == -1 ? -1 : (r - zeroGroups.get
          (zeroGroupIndex[r]).start + 1);
      final Pair<Integer, Integer> adjacentIndices = 

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-22

---
*Auto-pushed by [CodePush Extension](https://github.com)*
