# 20. Valid Parentheses

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
class Solution {
    public boolean isValid(String s) {
        if(s.length() % 2 == 1)
            return false;
        return isValid(0, ' ', s.toCharArray()) >= 0;
    }

    private int isValid(int i,char last, char[] s){
        if(i == s.length){
            return i;
        }
        if(i > s.length){
            return -1;

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-02

---
*Auto-pushed by [CodePush Extension](https://github.com)*
