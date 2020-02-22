# COUNTIF
*****
函数原型：COUNTIF(value1, [value2], ...,criteria)
*****
函数说明：统计满足条件的参数个数。
*****

例如：

- COUNTIF([1,2,3,4], ">2")，结果为2
- COUNTIF([1,2,3,4], "!=2")，结果为3
- COUNTIF([1,2,3,4], ">=1")，结果为4
- COUNTIF(["a", "b", "c"], "d")，结果为0

**举例：**

![](http://docfiles.baibaoyun.com/FtfFo97FHdZnKFNrXXfWCyxcfp-a)
结果如下图：

COUNTIF([90,95,91,88,92],">90")，所以大于90的只有95、91、92三个数，因此结果为3。
![](http://docfiles.baibaoyun.com/FiQBdYf1tBrtH6iIpwGbd2mbNBbL)
