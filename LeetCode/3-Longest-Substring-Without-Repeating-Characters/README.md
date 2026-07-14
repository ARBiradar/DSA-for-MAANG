# 3. Longest Substring Without Repeating Characters

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public int lengthOfLongestSubstring(String s) {

    int n = s.length();
        int maxLength = 0;
        
        // Array to store the last seen index of each character.
        // 128 covers all standard ASCII characters (letters, numbers, 
        symbols).
        int[] lastSeen = new int[128];
        
        // Initialize the array with -1 to indicate the character hasn't 
        been seen yet

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-14

---
*Auto-pushed by [CodePush Extension](https://github.com)*
