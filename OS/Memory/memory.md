# Memory

## Virtual Memory and Address Translation

1. Cache Structure
    - 组相联 (根据物理地址确定Set和Block, 遍历Cache line 对比Tag和valid位). 物理地址划分为Tag+Set-NO.+Block-No.
    - 替换算法 FIFO LRU
2. TLB 查询方式与Cache类似
3. [虚拟地址具体实现](https://zhuanlan.zhihu.com/p/65348145)


## Malloc and Free

1. `sbrk` and `mmap`
2. TCMalloc with Go