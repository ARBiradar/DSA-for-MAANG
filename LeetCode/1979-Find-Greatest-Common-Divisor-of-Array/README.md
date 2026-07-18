# 1979. Find Greatest Common Divisor of Array

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int largest = Integer.MIN_VALUE;

        // Find smallest and largest
        for (int num : nums) {
            if (num < smallest) smallest = num;
            if (num > largest) largest = num;
        }

        // Compute GCD using Euclidean Algorithm
        return gcd(smallest, largest);
                
    }
                int smallest = Integer.MAX_VALUE;
}

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-18

---
*Auto-pushed by [CodePush Extension](https://github.com)*
