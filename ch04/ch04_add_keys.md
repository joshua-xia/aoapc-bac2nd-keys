
[TOC]



# 补充题解 - 《经典》- 第 4 章 函数和递归

## ## 习题 4- 9 　 数据挖掘（ Data Mining, ACM/ICPC NEERC 2003, UVa1591）

考虑到$S_P​$和$S_Q​$的数据范围，A,B也一定是0到32之间的整数，那么完全可以考虑采用遍历所有A,B组合，对于指定的A,B，记$f(x, A,B)=(x + (x<<A))>>B​$，则Q数组占用的空间为$K=f(S_P*(N-1),A,B)+S_Q​$。寻找使得K最小的A,B即可。注意A,B还要满足$f(S_P, A,B)<S_Q​$，否则Q中元素的存储空间就会发生重叠。












