# 35. Search Insert Position

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
            if(target > nums[mid]){
                start = mid+1;
            }else if(target < nums[mid]){
                end = mid-1;
            } else return mid;
        }
        return start ;
        
    }
}

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-01

---
*Auto-pushed by [CodePush Extension](https://github.com)*
