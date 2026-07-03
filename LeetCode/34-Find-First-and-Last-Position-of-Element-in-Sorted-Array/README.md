# 34. Find First and Last Position of Element in Sorted Array

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
     public int[] searchRange(int[] nums, int target) {
        int[] ans = {-1,-1};
        int start = search(nums,target,true);
        int end  = search(nums,target,false); 
        ans[0] =start;
        ans[1] = end;
        return ans;
    
    }
     int search(int[] nums, int target, boolean isStart){ 
        int ans = -1;
        int start =0;

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-03

---
*Auto-pushed by [CodePush Extension](https://github.com)*
