# 1. Two Sum

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
    public int[] twoSum(int[] nums, int target) {
        int[] ans =  {-1,-1};
       for(int i =0; i< nums.length; i++){

        ans[0] = i;
        for(int j = i+1; j< nums.length; j++){
            if(target == nums[i] + nums[j] ){
                ans[1] = j;
                return ans;
            }
        }
       }
       return ans;
    }
}


```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-06-29

---
*Auto-pushed by [CodePush Extension](https://github.com)*
