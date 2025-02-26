# 8.1 什么是服务网格

2016 年，离开 Twiiter 的工程师 William Morgan 和 Oliver Gould 组建了一个小型技术公司 Buoyant。不久之后，他们在 Github 上发布了创业项目 Linkerd，业界第一款服务网格诞生！

那么，服务网格到底是什么？服务网格的概念最早由 William Morgan 在其博文《What’s a service mesh? And why do I need one?》中提出。作为服务网格的创造者，引用他的定义无疑是最官方和权威的。

:::tip 服务网格的定义

服务网格是一个处理服务通讯的专门的基础设施层。它的职责是在由云原生应用组成服务的复杂拓扑结构下进行可靠的请求传送。在实践中，它是一组和应用服务部署在一起的轻量级的网络代理，对应用服务透明。

:::right
 —— What’s a service mesh？And why do I need one?，William Morgan
:::

通过下述，感受服务网格从无到有、被社区接受、巨头入局、众人皆捧的发展历程：

- 2016 年 9 月：在 SF MicroServices 大会上，术语“Service Mesh”首次在公开场合提出，服务网格的概念从 Buoyant 公司内部走向社区。
- 2017 年 1 月：Linkerd 加入 CNCF，被归类到 CNCF 新设立的“Service Mesh”分类，这表明**服务网格的设计理念得到了主流社区认可**。
- 2017 年 4 月：Linkerd 发布 1.0 版本，服务网格实现了关键里程碑 —— 被客户接受，在生产环境中大规模应用。**服务网格从“虚”转“实”**。
- 2017 年 5 月：Google、IBM 和 Lyft 联合发布 Istio 0.1 版本，以 Istio 为代表的**第二代服务网格登场**。
- 2018 年 7 月：CNCF 发布了最新的云原生定义，将服务网格与微服务、容器、不可变基础设施等技术并列，**服务网格的地位空前提升**。
- 2022 年 7 月，Cilium 发布了“无边车模式”的服务网格，2 个月之后，Isito 发布了全新的数据平面模式 “Ambient Mesh”，服务网格的形态开始多元化。