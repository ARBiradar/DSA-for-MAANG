# 42. Trapping Rain Water

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public int trap(int[] height) {
        int n = height.length;
        int[] lm = new int[n];
        int[] rm = new int[n];
        lm[0] = height[0];
        rm[n-1] = height[n-1];
        for(int i =1; i<n ; i++){
            lm[i] = Math.max(height[i], lm[i-1]);
        }
        for(int i = n-2; i>= 0; i--){
            rm[i] = Math.max(height[i], rm[i+1]);
        }

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-12

---
*Auto-pushed by [CodePush Extension](https://github.com)*
