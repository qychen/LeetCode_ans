# DP

Flatting the inter-result space! See second o(n) space solution in:
https://leetcode.com/discuss/2143/any-better-solution-that-takes-less-than-space-while-in-time

Since the information in last step will just use once in very next step, we can flat the count[i][j] to just count[i] and save space!
