# 118. Pascal's Triangle

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
                if (j == 0 || j == i) {
                // First and last elements are always 1

                    row.add(1);
                }
                // Middle elements
                else {
                    int value = ans.get(i - 1).get(j - 1)
                              + ans.get(i - 1).get(j);
                    row.add(value);
                }
            }

            ans.add(row);
        }

   return ans;
    }
        
    

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-09

---
*Auto-pushed by [CodePush Extension](https://github.com)*
