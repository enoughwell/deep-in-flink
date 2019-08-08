# Deep in Flink
《[**Deep in Flink**](/deep-in-flink.md)》是对Flink的比较完整的机制及其实现的总结，不是简单的Flink中文文档的内容的摘录或者翻译，内容不会像Flink文档那样面面俱到，可以视作Flink文档之外的补充。

网上关于Flink的文章非常多，从Flink的基本开发、原理、源码解析，无所不包。经过近1年接触Flink，发现网上的内容过于零散，很少能有1篇文章或者系列文章，能够把Flink从全局到细节统一起来，让新接触Flink的人既有全局的视角，又能深入到Flink的细节设计之中，把握Flink的本质，不会望而生畏，特此编写。

另，类似于Flink的分布式计算引擎，如Spark、Storm等在原理上是相近的，深入解析Flink的原理，尽量抽取通用的概念，使读者对于分布式计算引擎领域能够更深的认识，则是更深层次的追求。

另会提供**PDF**和**EPUB**版本供大家阅读。

# 相关论文

- [Apache Flink™_ Stream and Batch Processing in a Single Engine](/papers/Apache_Flink_ Stream_and_Batch_Processing_in _a_Single_Engine.pdf)

  Apache Flink论文。

- [流上的高效模式匹配](/流上的高效模式匹配论文.md)
Flink的CEP实现重度参考了论文《[Efficient Pattern Matching over Event Streams](https://people.cs.umass.edu/~immerman/pub/sase+sigmod08.pdf)》，此文是该论文核心部分的中文版。

- [Volcano-An Extensible and Parallel Query Evaluation System](/papers/volcano.pdf)
可扩展的并行查询系统模型，所有的SQL查询基本都参考过该论文。


- [流计算SQL](/papers/One_SQL_to_Rule_Them_All.pdf)
SIGMOD'19 Apache Beam/Calcite/Flink & 流式SQL

- [Trill: A high-performance incremental query processor for diverse analytics](/papers/Trill_A High-Performance-Incremental-Query-Processor-for-Diverse-Analytics.pdf)
微软出品，基于时序数据和查询模型，可处理实时和离线数据。Trill 可用作流引擎，轻量级内存关系引擎，以及渐进式查询处理器。Trill 
可以做到每天处理一兆次（trillion，一万亿）事件，比当今市场上的流分析引擎的数据处理速度快2-4倍。

- [FlinkCL-An-OpenCL-Based In-Memory](/papers/FlinkCL-An-OpenCL-Based In-Memory_Cen-Chen-IEEE-TC-2018.pdf)
Flink与OpenCL结合应用。

- [GFlink An In-Memory Computing Architecture on Heterogeneous CPU-GPU Clusters for Big Data](/papers/GFlink-An-In-Memory-Computing-Architecture-on-Heterogeneous-CPU-GPU-Clusters-for-Big-Data.pdf)
基于Flink的CPU-GPU混合集群。

- [MillWheel Fault-Tolerant Stream Processing atInternet Scale](/papers/MillWheel_Fault-Tolerant_Stream_Processing_at_Internet_Scale.pdf)
  Google的实时大规模流式处理系统MillWheel,Google流批统一的大数据处理平台Cloud DataFlow的前身。

- [Streaming Auto-Scaling in Google Cloud Dataflow](./papers/Streaming_Auto-Scaling_in_Google_Cloud_Dataflow.pdf)
Google dataflow 流计算自动扩展收缩机制。

- [Low latency stream processing: Apache Heron with Infiniband & Intel Omni-Path](/papers/Heron_Infiniband.pdf)
Twitter Heron基于高速、高带宽Infiniband网络提供的低延迟数据处理实践。