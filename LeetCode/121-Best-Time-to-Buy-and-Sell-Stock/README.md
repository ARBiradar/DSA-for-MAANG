# 121. Best Time to Buy and Sell Stock

![Platform](https://img.shields.io/badge/Platform-LeetCode-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-orange) ![Language](https://img.shields.io/badge/Language-Unknown-green)

## 🧩 Problem Summary

See the original problem on LeetCode

## 💻 Solution

```unknown
        int buyingPrice = Integer.MAX_VALUE;
        int maxProfit = 0;
        for(int i = 0; i< prices.length; i++){
            int sellingPrice = prices[i];
            if(sellingPrice > buyingPrice ){
                int profit = sellingPrice - buyingPrice;
            }
                maxProfit = Math.max(maxProfit , profit);
            else{
                buyingPrice = sellingPrice;
            }
    public int maxProfit(int[] prices) {
        }
        return maxProfit;

```

## 🏷️ Tags

`LeetCode` `Coding` `Unknown`

## 📅 Solved On

2026-07-15

---
*Auto-pushed by [CodePush Extension](https://github.com)*
