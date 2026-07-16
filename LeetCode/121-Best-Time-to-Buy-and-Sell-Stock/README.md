# 121. Best Time to Buy and Sell Stock

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int maxProfit = 0;
        int buyPrice = Integer.MAX_VALUE;

        for(int i = 0; i < prices.length; i++){
            if(buyPrice > prices[i]){
                buyPrice = prices[i];
            }
            int profit = prices[i]-buyPrice;
            if(profit > maxProfit){
                maxProfit = profit;
            }
        }
        return maxProfit;
    }

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-16

---
*Auto-pushed by [CodePush Extension](https://github.com)*
