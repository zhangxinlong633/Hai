# benchmark

## 概述
    按正常使用的方式来做benchmark. 
    第一阶段: 10亿条
    第二阶段: 1万亿条
    
## array
    列式存储的使用方式
    
    bench环境:
    MacBook Pro (13-inch, 2017, Two Thunderbolt 3 ports)/2.3 GHz Intel Core i5/8 GB 2133 MHz LPDDR3/256GB disk.
 
    写入文件:
    -rwxr-xr-x  1 zhangxinlong  staff   3.7G  4 19 19:07 first
    结果: 
     array bench count: 1000000000, from 1587294439 to 1587294447, speed: 125000000
     
    1.25亿/秒 ,一个记录大小4字节.
     
   
