# Go

## Go的运行机制

1. 函数值传递, slice 作为函数参数
2. interface的底层机制
3. map, slice的底层机制, Go sync.map
4. Go的内存分配策略, TCMalloc, libC malloc机制 (Go runtime, C runtime).
    - Malloc in C is introduced in CSAPP
    - GO GC can be found [here](https://draveness.me/golang/docs/part3-runtime/ch07-memory/golang-garbage-collector/)
5. Go GC 策略, 优点与不足之处.
6. Go编译时期的内存逃逸分析, 为什么Go函数中可以返回局部变量的指针.
7. 为什么说Go中的func是一等公民.

## Go的并发原语

1. Goroutine的机制, NJU-OSLab coroutine的实现. 协程, 线程, 进程.
2. 读写锁, 互斥锁, SpinLock, NJU-OSLab 锁的实现
3. GMP调度

## 题目

1. [Geektutu Go 面试题](https://geektutu.com/post/qa-golang.html)
2. [知乎回答](https://www.zhihu.com/question/60952598)