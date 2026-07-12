# 22. Generate Parentheses

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public List<String> generateParenthesis(int n) {
          List<String> result = new ArrayList<>();
          backtrack(result, "", 0, 0, n);
        return result;
    }

    private void backtrack(List<String> result, String current, int open, 
    int close, int max) {
        if (current.length() == max * 2) {
            result.add(current);
            return;
        }

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-12

---
*Auto-pushed by [CodePush Extension](https://github.com)*
