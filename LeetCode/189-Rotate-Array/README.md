# 189. Rotate Array

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public void rotate(int[] nums, int k) {
        int i =0; int j= nums.length;
        k = k%j;
        arrayReverse(nums,0,j-1);
        arrayReverse(nums,0,k-1);
        arrayReverse(nums,k,nums.length-1);

        
    }
    public void arrayReverse(int[] ans, int 
    i, int j){

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-06-30

---
*Auto-pushed by [CodePush Extension](https://github.com)*
