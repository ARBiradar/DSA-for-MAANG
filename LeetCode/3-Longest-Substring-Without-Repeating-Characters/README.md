# 3. Longest Substring Without Repeating Characters

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        
        // Initialize the array with -1 to indicate the character hasn't 
        been seen yet
        for (int i = 0; i < 128; i++) {
            lastSeen[i] = -1;
        }
        
        int left = 0; // Left boundary of our sliding window
        
        for (int right = 0; right < n; right++) {
            char currentChar = s.charAt(right);
            
            // If we've seen this character before AND it falls inside our 
            current window...

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-11

---
*Auto-pushed by [CodePush Extension](https://github.com)*
