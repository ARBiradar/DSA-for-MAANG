# 1929. Concatenation of Array

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public int[] getConcatenation(int[] nums) {
        int n = nums.length;
        int[] arr = new int[2 * n];
        for(int i = 0; i<nums.length;i++){
            arr[i]=nums[i];
            arr[i+n] = nums[i];
        }
        
        return arr;
        
    }
}

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-19

---
*Auto-pushed by [CodePush Extension](https://github.com)*
