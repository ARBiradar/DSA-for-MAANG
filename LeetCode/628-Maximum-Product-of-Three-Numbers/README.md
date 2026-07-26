# 628. Maximum Product of Three Numbers

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int n = nums.length;
        
        // Case 1: product of last three (largest)
        int option1 = nums[n-1] * nums[n-2] * nums[n-3];
        
        // Case 2: product of two smallest (negative) and largest
        int option2 = nums[0] * nums[1] * nums[n-1];
        
        return Math.max(option1, option2);
    }
}


```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-26

---
*Auto-pushed by [CodePush Extension](https://github.com)*
