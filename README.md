# Memcached

[Memcached](http://memcached.org/)  是一个高性能的分布式内存对象缓存系统，用于动态Web应用以减轻数据库负载。


## 介绍

该应用模板会使用 [Helm](https://helm.sh) 包管理工具在 [Kubernetes](http://kubernetes.io) 上启动一个 [Memcached](http://memcached.org/) 集群.


helm 目录里为helm模板。

两个yaml文件为k8s部署文件。

创建集群需使用 memagent 来给memcached建立连接。
