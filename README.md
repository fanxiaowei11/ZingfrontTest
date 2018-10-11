# 题目描述

> 

## 思路

``` 
题目一
  1.先将字符串统一大小写
  2.单词是通过空格隔开的所以可以通过空格切割，
  将字符串转化成数组，然后找出数组的相同项
  3.将第二步得到的数组的每一项的长度拿出来重
  新组成数组，并且去掉重复项，并且按到从大到
  小的顺序排列，取出数组的第二项（即求得单词
  的长度）
  4.循环第二步得到的数组，找到长度为第三步得
  到的长度的那一项输出（即等到所求）

  测试结果 
  <img src="https://github.com/fanxiaowei11/ZingfrontTest/blob/master/img/demo1.png" width="411" height="134">
  
题目二
    假设数字为n，数字拆分至少是2个数字，所以
    这个数字的开始位置必须小于n/2，结束位置
    必须小于（n/2）+1。接下来两个循环，第一
    次层从1开始，到n/2结束，来确定拆分数字的
    开始位置。第二次循环用来判断累加的结果是
    否等于n，若等于n则符合要求
  
   测试结果
   <img src="https://github.com/fanxiaowei11/ZingfrontTest/blob/master/img/demo2.png" width="391" height="225">
   <img src="https://github.com/fanxiaowei11/ZingfrontTest/blob/master/img/demo3.png" width="391" height="225">
```