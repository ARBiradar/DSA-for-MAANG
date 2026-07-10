# 42. Trapping Rain Water

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
            rm[i] = Math.max(height[i], rm[i+1]);
        }
        int trpWtr = 0;
        for(int i = n-2; i>= 0; i--){
        }
            lm[i] = Math.max(height[i], lm[i-1]);
        for(int i =1; i<n ; i++){
        rm[n-1] = height[n-1];
        for(int i =0; i<n; i++){
            trpWtr += waterLevel - height[i];
        }
        lm[0] = height[0];
        int[] rm = new int[n];
        int[] lm = new int[n];
            int waterLevel = Math.min(lm[i],rm[i]);

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-10

---
*Auto-pushed by [CodePush Extension](https://github.com)*
