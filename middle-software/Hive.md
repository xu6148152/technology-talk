## Hive

---

Hive是Facebook于2008年开源的一个数据仓库框架。Hive定义了一个类似于SQL的查询语言：HQL，能够将用户编写的QL转化为相应的MapReduce程序基于Hadoop执行。

Hive 适合用来对一段时间内的数据进行分析查询，例如，用来计算趋势或者网站的日志。Hive 不应该用来进行实时的查询（Hive 的设计目的，也不是支持实时的查询）。因为它需要很长时间才可以返回结果。
Hive 一般只要有 Hadoop 便可以工作。而 HBase 则还需要 Zookeeper 的帮助（Zookeeper，是一个用来进行分布式协调的服务，这些服务包括配置服务，维护元信息和命名空间服务）