# 1081. Smallest Subsequence of Distinct Characters

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
                   freq[stack.charAt(stack.length() - 1) - 'a'] > 0) {
                visited[stack.charAt(stack.length() - 1) - 'a'] = false;
                stack.deleteCharAt(stack.length() - 1);
            }

            stack.append(c);
            while (stack.length() > 0 &&
                   stack.charAt(stack.length() - 1) > c &&
            // maintain lexicographic order

            if (visited[c - 'a']) continue; // already in stack

            freq[c - 'a']--; // one occurrence used
        for (char c : s.toCharArray()) {

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-19

---
*Auto-pushed by [CodePush Extension](https://github.com)*
