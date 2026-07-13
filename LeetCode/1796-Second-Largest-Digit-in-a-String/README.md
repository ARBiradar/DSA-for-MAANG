# 1796. Second Largest Digit in a String

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public int secondHighest(String s) {
      int max = -1;
        int secMax = -1;

        for (char c : s.toCharArray()) {
            if (Character.isDigit(c)) {
                int num = c - '0'; // convert char digit to int
                if (num > max) {
                    secMax = max;
                    max = num;
                } else if (num < max && num > secMax) {
                    secMax = num;

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-13

---
*Auto-pushed by [CodePush Extension](https://github.com)*
