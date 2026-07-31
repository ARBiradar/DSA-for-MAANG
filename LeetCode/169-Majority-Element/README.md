# 169. Majority Element

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
    }
    return (freq > nums.length/2) ? candidate : -1;
    // Optional: Verify candidate
    int freq = 0;
    for (int num : nums) {
        if (num == candidate) freq++;
        count += (num == candidate) ? 1 : -1;
    }
    public int majorityElement(int[] nums) {
         int candidate = 0, count = 0;
    for (int num : nums) {
        if (count == 0) candidate = num;
class Solution {

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-31

---
*Auto-pushed by [CodePush Extension](https://github.com)*
