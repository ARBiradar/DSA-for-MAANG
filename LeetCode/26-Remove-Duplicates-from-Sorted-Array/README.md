# 26. Remove Duplicates from Sorted Array

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public int removeDuplicates(int[] nums) {
        int j =1;
        for(int i =1; i<nums.length; i++){
            if(nums[j-1] != nums[i]){
                nums[j] = nums[i];
                j++;
            }
        }
        return j;
        
    }
}

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-19

---
*Auto-pushed by [CodePush Extension](https://github.com)*
