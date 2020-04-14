# PAT Advanced 题目

> 题目考点以及基础坑点总结

1. [1003 Emergency（最短路）](https://joke-lin.top/2020/02/24/2020-02-24-PAT-Advanced-1003/)

2. [1010 Radix（二分法）](https://joke-lin.top/2020/03/19/2020-03-19-PAT-Advanced-1010/)

3. [1012 The Best Rank（排序）](https://joke-lin.top/2020/03/21/2020-03-21-PAT-Advanced-1012/)

	需要四舍五入，以及并列排名：1 1 3 4 5 这种（没有第二名了就）

4. [1014 Waiting in Line（优先队列）](https://joke-lin.top/2020/03/21/2020-03-24-PAT-Advanced-1014/)

	17：00后的不予服务，只要在17：00之前接受服务的都可以，不用管截止时间。

5. [1016 Phone Bills（排序）](https://joke-lin.top/2020/03/27/2020-03-27-PAT-Advanced-1016/)

	没有符合条件的时间对时，不输出该用户信息。。

6. [1017 Queueing at Bank（优先队列）](https://joke-lin.top/2020/03/29/2020-03-29-PAT-Advanced-1017/)

	17：00之后不能被服务，17：00 是到达时间。。不是服务时间，服务时间不能超过1小时是指大于1小时的按一小时处理，而不是不处理

7. [1018 Public Bike Management（Dijkstra + DFS）](https://joke-lin.top/2020/03/31/2020-03-31-PAT-Advanced-1018/)

	在计算携带数量和带回数量的时候需要考虑先后关系，即后面多余的车不能补充前面的。

8. [1020 Tree Traversals （二叉树）](https://joke-lin.top/2020/04/01/2020-04-01-PAT-Advanced-1020/)

9. [1021 Deepest Root （连通分量+树的直径）](https://joke-lin.top/2020/04/03/2020-04-03-PAT-Advanced-1021/)

10. 1022 Digital Library（Map的使用）

	注意数据的保存，id保存为int的时候注意输出仍然是7位，据说year可能超出题目限定的范围，所以都用string保存的好。。

11. 1024 Palindromic Number（大整数相加）

	字符串相加，注意一开始不要用int读入，会溢出。。。

12. [1026 Table Tennis（模拟）](https://joke-lin.top/2020/04/09/2020-04-09-PAT-Advanced-1026/)

	最后测试点坑点：在检查是否有VIP在排队的时候，忽略了此VIP用户可能在之前以及被处理（VIP有时候可以优先）

13. 1028 List Sorting（排序）

	**注意不要使用`std::cout`可能会超时。。。**

14. 1031 Hello World for U（打印）

	题目看清满足尽可能方块的同时需要满足 n2 > n1

15. [1032 Sharing（链表）](https://joke-lin.top/2020/04/11/2020-04-11-PAT-Advanced-1032/)

	注意特殊情况，考虑问题要全面，路径不以-1结尾也是存在

16. [1033 To Fill or Not to Fill （贪心）](https://joke-lin.top/2020/04/11/2020-04-11-PAT-Advanced-1033/)

17. 1034 Head of a Gang（DFS，图的遍历）

	注意输入。。。

18. 1035 Password（字符串）

	注意输出，单复数，题目看清。。