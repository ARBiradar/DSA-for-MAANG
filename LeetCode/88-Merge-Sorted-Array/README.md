# 88. Merge Sorted Array

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public void merge(int[] nums1, int m, int[] nums2, int n) {
          int i = m - 1; // Pointer for the end of the actual elements in 
          nums1
    int j = n - 1; // Pointer for the end of nums2
    int k = m + n - 1; // Pointer for the end of the merged array

    while (i >= 0 && j >= 0) {
        if (nums1[i] > nums2[j]) {
            nums1[k] = nums1[i];
            i--;
        } else {
            nums1[k] = nums2[j];

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-12

---
*Auto-pushed by [CodePush Extension](https://github.com)*
