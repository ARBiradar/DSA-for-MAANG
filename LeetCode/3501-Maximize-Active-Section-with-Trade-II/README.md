# 3501. Maximize Active Section with Trade II

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
                                  ones + st.query(startAdjacentGroupIndex, 
                                  endAdjacentGroupIndex));
      if (s.charAt(l) == '0' &&
          zeroGroupIndex[l] + 1 <= (s.charAt(r) == '1' ? zeroGroupIndex[r] : 
          zeroGroupIndex[r] - 1))
        activeSections =
            Math.max(activeSections, ones + left + zeroGroups.get
            (zeroGroupIndex[l] + 1).length);
      if (s.charAt(r) == '0' && zeroGroupIndex[l] < zeroGroupIndex[r] - 1)
        activeSections =
            Math.max(activeSections, ones + right + zeroGroups.get
            (zeroGroupIndex[r] - 1).length);
      ans.add(activeSections);
    }

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-26

---
*Auto-pushed by [CodePush Extension](https://github.com)*
