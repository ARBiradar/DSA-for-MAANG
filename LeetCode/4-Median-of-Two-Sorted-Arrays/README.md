# 4. Median of Two Sorted Arrays

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int result[] = new int[nums1.length + nums2.length];
      
        int num = nums1.length + nums2.length-2;
        
    System.arraycopy(nums1, 0, result, 0, nums1.length);
        
        // Copy the second array into the result starting right after the first array
       System.arraycopy(nums2, 0, result, nums1.length, nums2.length);
    Arrays.sort(result);
        
        int n = result.length;
        
        // 3. CRITICAL FIX: Correct Median Math
        if (n % 2 != 0) {
            // If total length is odd, return the exact middle element
            return result[n / 2];
        } else {
            // If total length is even, return the average of the two middle elements
            return (result[(n / 2) - 1] + result[n / 2]) / 2.0;

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-08

---
*Auto-pushed by [CodePush Extension](https://github.com)*
