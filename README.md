# Bubble-Sort
a simple demo developed by javascript to descibe bubble-sort algorithm

### 简介

实现基本思路：冒泡排序是经过n-1趟子排序完成的，第i趟子排序从第1个数至第n-i个数，若第i个数比后一个数大（则升序，小则降序）则交换两数。

稳定性 时间复杂度为O（n^2）

冒泡排序：最简单，也最慢，貌似长度小于7最优
插入排序： 比冒泡快，比快速排序和希尔排序慢，较小数据有优势
快速排序：这是一个非常快的排序方式，V8的sort方法就使用快速排序和插入排序的结合
希尔排序：在非chrome下数组长度小于1000，希尔排序比快速更快
系统方法：在forfox下系统的这个方法非常快


