# Clos 网络

### 概述

对 crossbar 结构进行改进

crossbar 是有阻塞的，并且规模有限，而且只能 N × N 不能 M × N

用 Clos 即节约了成本又增加了效率

### Clos 应用

1. 交换机内部 
2. 网络架构

### 常见问题

#### 为了 nonblocking,要多少个 middle-stage?
当 n-n 时，2n-1 个，因为 source 的 neighbor 可能占用 n-1 个，dst 的 neighbor 也可能占用 n-1 个。所以至少还要多一个，所以 2n-1 个。

#### 可以折叠，从 Three-Stage Clos Network 变成 Fat-tree Network


## 参考

[https://www.zhihu.com/question/48343492](https://www.zhihu.com/question/48343492)

