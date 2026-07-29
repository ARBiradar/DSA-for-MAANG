# 1081. Smallest Subsequence of Distinct Characters

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
    for (final char c : text.toCharArray()) { --count[c]; if (used[c]) 
    continue; 
    while (sb.length() > 0 && last(sb) > c && count[last(sb)] > 0) 
    { used[last(sb)] = false; sb.setLength(sb.length() - 1); }
     used[c] = true; sb.append(c); } return sb.toString(); }
      private char last(StringBuilder sb) { 
        return sb.charAt(sb.length() - 1);
         }
          }

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-29

---
*Auto-pushed by [CodePush Extension](https://github.com)*
