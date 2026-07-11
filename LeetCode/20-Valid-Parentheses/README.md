# 20. Valid Parentheses

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        }
        if(i > s.length){
            return -1;
        }

        if(s[i] == '(' || s[i] == '{' || s[i] == '['){
            int next = isValid(i + 1, s[i], s);
            return next < 0 ? -1 : isValid(next + 1, last, s);
        }

        if(s[i] == ')' && last == '(' || s[i] == ']' && last == '[' ||s[i] 
        == '}' && last == '{'){
            return i;
        }

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-11

---
*Auto-pushed by [CodePush Extension](https://github.com)*
