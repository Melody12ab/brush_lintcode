Q:设计一个算法，找出只含素因子2，3，5 的第 n 小的数。符合条件的数如：1, 2, 3, 4, 5, 6, 8, 9, 10, 12...

A:希望丑数是按从小到大顺序生成的，我们把得到的第一个乘以2后大于M的结果，记为M2。 同样我们把已有的每一个丑数乘以3和5，能得到第一个大于M的结果M3和M5。那么下一个丑数应该是M2、M3和M5三个数的最小者。```ugly=2^n*3^m*5^p```
