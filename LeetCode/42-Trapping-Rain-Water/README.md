# 42. Trapping Rain Water

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int trpWtr = 0;
        for(int i =0; i<n; i++){
            int waterLevel = Math.min(lm[i],rm[i]);
            trpWtr += waterLevel - height[i];
        }
       return trpWtr; 
    }
    
}

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-16

---
*Auto-pushed by [CodePush Extension](https://github.com)*
