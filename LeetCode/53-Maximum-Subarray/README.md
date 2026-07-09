# 53. Maximum Subarray

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int maxSum = Integer.MIN_VALUE;
        for(int i= 0; i< nums.length; i++){
            currSum = currSum + nums[i];
            maxSum = maxSum<currSum?currSum:maxSum;
            currSum = currSum<0?0:currSum;
        }
        return maxSum;

    }
}
class Solution {
    public int maxSubArray(int[] nums) {
        
        int currSum =0;

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-09

---
*Auto-pushed by [CodePush Extension](https://github.com)*
