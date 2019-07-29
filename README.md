# [**Deep in Flink**](/deep-in-flink.md)
本文不是简单的Flink中文文档的内容的摘录或者翻译，内容不会像Flink文档那样面面俱到，可以视作Flink文档之外的补充。

网上关于Flink的文章非常多，从Flink的基本开发、原理、源码解析，无所不包。经过近1年接触Flink，发现网上的内容过于零散，很少能有1篇文章或者系列文章，能够把Flink从全局到细节统一起来，让新接触Flink的人既有全局的视角，又能深入到Flink的细节设计之中，把握Flink的本质，不会望而生畏，特此编写。

另，类似于Flink的分布式计算引擎，如Spark、Storm等在原理上是相近的，深入解析Flink的原理，尽量抽取通用的概念，使读者对于分布式计算引擎领域能够更深的认识，则是更深层次的追求。

另会提供**PDF**和**EPUB**版本供大家阅读。


# [**流上的高效模式匹配**](/流上的高效模式匹配论文.md)
Flink的CEP实现重度参考了论文《[Efficient Pattern Matching over Event Streams](https://people.cs.umass.edu/~immerman/pub/sase+sigmod08.pdf)》，此文是该论文核心部分的中文版。

# [**Volcano-An Extensible and Parallel Query Evaluation System**](/papers/volcano.pdf)
可扩展的并行查询系统模型，所有的SQL查询基本都参考过该论文。


# [流计算SQL](/papers/One_SQL_to_Rule_Them_All.pdf)
SIGMOD'19 Apache Beam/Calcite/Flink & 流式SQL

