# A Very Big Sum

![Platform](https://img.shields.io/badge/Platform-HackerRank-blue) ![Difficulty](https://img.shields.io/badge/Difficulty-AuthorvatsalchananaDifficultyEasyMax Score10Submitted By2273009-orange) ![Language](https://img.shields.io/badge/Language-python3-green)

## 🧩 Problem Summary

.MathJax_SVG_Display {text-align: center; margin: 1em 0em; position: relative; display: block!important; text-indent: 0; max-width: none; max-height: none; min-width: 0; min-height: 0; width: 100%}
.MathJax_SVG .MJX-monospace {font-family: monospace}
.MathJax_SVG .MJX-sans-serif {font-family: sans-serif}
.MathJax_SVG {display: inline; font-style: normal; font-weight: normal; line-height: normal; font-size: 100%; font-size-adjust: none; text-indent: 0; text-align: left; text-transform: none; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0; min-height: 0; border: 0; padding: 0; margin: 0}
.MathJax_SVG * {transition: none; -webkit-transition: none; -moz-transition: none; -ms-transition: none; -o-transition: none}
.mjx-svg-href {fill: blue; stroke: blue}
.MathJax_SVG_LineBox {display: table!important}
.MathJax_SVG_LineBox span {display: table-cell!important; width: 10000em!imp

## 💻 Solution

```python3
    }

}

public class Solution {
    public static void main(String[] args) throws IOException {
        BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));
        BufferedWriter bufferedWriter = new BufferedWriter(new FileWriter(System.getenv
        ("OUTPUT_PATH")));

        int arCount = Integer.parseInt(bufferedReader.readLine().trim());

        String[] arTemp = bufferedReader.readLine().replaceAll("\\s+$", "").split(" ");

        List<Long> ar = new ArrayList<>();

        for (int i = 0; i < arCount; i++) {
            long arItem = Long.parseLong(arTemp[i]);
            ar.add(arItem);
        }

        long result = Result.aVeryBigSum(ar);

        bufferedWriter.write(String.valueOf(result));
        bufferedWriter.newLine();

        bufferedReader.close();
        bufferedWriter.close();
    }
}

```

## 🏷️ Tags

`HackerRank` `Coding` `python3`

## 📅 Solved On

2026-07-07

---
*Auto-pushed by [CodePush Extension](https://github.com)*
