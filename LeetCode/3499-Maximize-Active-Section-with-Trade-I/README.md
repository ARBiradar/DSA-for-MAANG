# 3499. Maximize Active Section with Trade I

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public int maxActiveSectionsAfterTrade(String s) {
        int oneCount = 0; // Total number of ones already present in 
        the string
        int maxMergedzeros = 0; // Max number ofg aditional ones we 
        could get by merging 2 0 blocks
        int currZeroCount = 0; // Length of the zero block we are 
        currently walking through
        int lastZeroCount = 0; // Length of the previous 0 block we 
        finished

        // Loop over each char
        for(char c : s.toCharArray()){
            if(c == '0') currZeroCount++; // Increase the continuos 

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-22

---
*Auto-pushed by [CodePush Extension](https://github.com)*
