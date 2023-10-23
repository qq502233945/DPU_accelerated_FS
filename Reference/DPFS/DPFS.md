# 论文阅读记录
## 作者/机构
IBM
## 开源内容
### Docs
[ACM DL](https://dl.acm.org/doi/10.1145/3579370.3594769)

[OpenFabrics Alliance Workshop '23 Slides](https://www.openfabrics.org/wp-content/uploads/2023-workshop/2023-workshop-presentations/day-3/303_PGootzen.pdf)
### Code
[Github DPFS](https://github.com/qicosmos/rest_rpc)
## 背景
分布式文件系统（HadoopFs，Ceph, GluseterFs）以及云原生文件系统(Amazon EFS , AliBaba Pangu,Azure Files)被广泛运用于云存储领域.

但是构建一个高性能弹性云原生文件系统是具有挑战的。1）网络以及存储性能的增长速度远高于CPU性能增长，需要使用更多CPU资源满足设备性能。2）客户端逻辑臃肿，通常包括了元数据/数据服务器的通讯与协调，缓存管理等功能。每个客户端可能消耗GB级别的DRAM来实现（比如juiceFS，缓存还可能占用本地存储一半的容量）。这也限制了一台服务器上容纳虚拟机或者容器的数量。
## Motivation

## Desigen

## Experiment
### 关键指标分析
### 实验结果

##Key Insight

