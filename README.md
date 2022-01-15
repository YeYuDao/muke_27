# muke_27
Dubbo 3 深度剖析 - 透过源码认识你
Dubbo 3 深度剖析 - 透过源码认识你
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 构建 Apache Dubbo 3 脚手架，开启奇幻之旅 

#### 本章中，将使用 Apache Dubbo 3 和 Springboot 构建一套 Consumer 和 Provider 的脚手架，帮助大家了解目前互联网主流脚手架构建和使用方式，并进行多种构建方式的比较和分析。
1-1 Hello，Apache Dubbo 3 (06:43)

1-2 本章概览 (03:50)

1-3 了解 Dubbo (08:38)

1-4 快速构建 Provider 和 Consumer (03:48)

1-5 构建业务公共模块 (07:41)

1-6 集成 Dubbo 配置文件 (08:38)

1-7 Provider 使用演示 (02:56)

1-8 Consumer 集成演示 (04:35)

1-9 Dubbo 高层架构介绍 (05:33)

1-10 面试点：Dubbo 与其他微服务框架的比较 (04:58)

1-11 【查缺补漏】Zookeeper安装---Windows

1-12 【查缺补漏】Zookeeper安装---Linux

1-13 【知识拓展】Spring整合Dubbo脚手架构建

1-14 【知识拓展】SpringBoot整合Dubbo脚手架构建

1-15 Springboot 脚手架搭建【拓展配套代码】 (13:07)


### 第2章 Apache Dubbo 3 的“人才市场”，服务注册和服务订阅流程分析

#### 本章中，将结合 Apache Dubbo 3 的服务启动、服务注册以及服务订阅等流程进行源码分析，并对 Apache Dubbo 3 的新特性---应用级发现进行剖析。
2-1 本章概览 (02:57)

2-2 课前准备工作【必做】 (02:35)

2-3 下载Dubbo和Dubbo-Admin源码 (03:04)

2-4 Dubbo-admin介绍 (01:40)

2-5 Dubbo-admin编译部署 (14:17)

2-6 开发架构图概述 (07:32)

2-7 【查缺补漏】zookeeper概要学习 (10:04)

2-8 dubbo 3注册中心数据结构讲解 (19:19)

2-9 URL举例解析 (03:56)

2-10 服务提供者注册流程源码解析 (10:27)

2-11 Dubbo3.0注册流程源码解析 (17:11)

2-12 服务启动流程（上） (08:14)

2-13 服务启动流程（下） (12:48)

2-14 Provider和Consumer双版本支持参数讲解 (03:35)

2-15 Dubbo3.x版本Provider注册源码讲解 (04:12)

2-16 Dubbo3.x版本Consumer订阅流程讲解 (16:45)

2-17 migrateToApplicationFirstInvoker流程讲解 (07:49)

2-18 ZookeeperRegistry.java源码解析 (16:28)

2-19 refreshServiceDiscoveryInvoker流程讲解 (11:31)

2-20 本章小结 (05:37)


### 第3章 Apache Dubbo 3 的“前台”，服务暴露和服务调用流程分析 

#### 大家都知道 Apache Dubbo 的底层是 Netty，那是如何进行工作的呢？ 本章节就是讲述如何进行 Netty 的服务暴露和调用，并且讲解高级特性中的本地调用和直连服务是如何进行处理的，让我们一起逐渐揭开 Apache Dubbo 的面纱吧。
3-1 本章概览 (02:03)

3-2 RPC基础概念介绍 (04:34)

3-3 RPC核心组件讲解 (14:39)

3-4 Dubbo调用流程图解 (04:38)

3-5 高级特性演示：本地调用 (09:58)

3-6 injvm服务暴露源码剖析 (11:36)

3-7 export和invoker介绍 (07:25)

3-8 injvm服务调用源码剖析 (10:19)

3-9 本地调用小结 (02:14)

3-10 直连提供者流程分析 (03:17)

3-11 Dubbo服务暴露流程引入 (02:49)

3-12 Dubbo Netty服务暴露源码分析 (17:45)

3-13 Dubbo Netty服务暴露总结 (09:04)

3-14 Dubbo Consumer核心功能点讲解 (05:13)

3-15 Dubbo Consumer三种调用Provider方式源码讲解 (09:05)

3-16 InvokerInvocationHandler生成 (05:51)

3-17 本章小结 (01:56)


### 第4章 Apache Dubbo 3的“通信密码”，Dubbo 协议和序列化分析 

#### 一款优秀的协议应该具备哪些特性？ 本章节会带领大家从 Dubbo 协议入手，讲述一款优秀的协议的组成部分和工作流程。
4-1 本章概览 (02:52)

4-2 网络协议基本概念引入 (02:28)

4-3 协议定义与序列化讲解 (14:15)

4-4 int类型序列化示例 (06:01)

4-5 int类型反序列化示例 (13:35)

4-6 Dubbo协议解析入口讲解 (02:58)

4-7 dubbo请求编码源码解析 (11:52)

4-8 图解dubbo请求编码 (07:19)

4-9 Dubbo请求接收解码讲解 (12:38)

4-10 Dubbo响应编码封装解析 (05:37)

4-11 Dubbo响应解码拆包解析 (03:55)

4-12 本章小结 (04:44)


### 第5章 Apache Dubbo 3 的“影分身之术”，Dubbo 线程与线程池分析

#### Apache Dubbo 的高性能同样体现在线程和线程池的使用上，本章节就带领大家了解Apache Dubbo 的“影分身之术”
5-1 本章概览 (02:50)

5-2 Dubbo线程与线程池使用流程 (02:20)

5-3 Dubbo线程模型类型介绍 (05:09)

5-4 Dubbo线程模型配置及演示 (02:23)

5-5 Dubbo线程模型执行流程讲解 (12:52)

5-6 Dubbo线程模型三种类型源码讲解 (14:16)

5-7 Dubbo线程模型工作流程讲解 (12:37)

5-8 Dubbo线程模型区别和取舍 (09:52)

5-9 Dubbo线程池概况 (03:39)

5-10 Fixed线程池源码解析和配置 (05:05)

5-11 Dubbo线程池确认时机 (03:22)

5-12 limited线程池源码解析和配置 (02:33)

5-13 Cached线程池源码解析和配置 (02:03)

5-14 eager线程池源码解析 (07:42)

5-15 多种线程池的选择 (03:52)

5-16 线程池数量设置思考 (05:53)


### 第6章 Apache Dubbo 3 的"附加服务”，Dubbo 核心功能 Filter

#### 本章节主要针对 Dubbo 核心之一的 Filter 进行讲解，并结合之前课程的内容，讲解Filter的工作原理和工作流程。
6-1 本章概览 (01:43)

6-2 浅谈Dubbo Filter (02:11)

6-3 图解Dubbo Filter运行流程 (05:25)

6-4 自定义专属Filter (05:31)

6-5 配置Filter的两种方式 (06:36)

6-6 Dubbo Filter加载时机 (05:30)

6-7 AccessLogFilter配置及源码讲解 (08:34)

6-8 ExecutionLimitFilter配置及源码讲解 (12:21)

6-9 ClassLoadFilter源码和实现原理讲解 (06:55)

6-10 Dubbo高级特性之隐式参数传递演示 (06:37)

6-11 InternalThreadLocal源码讲解 (07:55)

6-12 ContextFilter源码和实现原理讲解 (05:09)

6-13 ConsumerContextFilter源码和实现原理讲解 (02:40)

6-14 ActiveLimitFilter演示及源码讲解 (03:16)

6-15 实际项目常见Filter扩展 (07:08)

6-16 本章小结 (03:44)


### 第7章 Apache Dubbo 3 的“十八般武艺”，Dubbo 高级功能解析

#### 本章节主要针对“隐式参数传递”、“ Dubbo 全链路异步”、“ Dubbo 并发控制”等多项高级功能进行剖析。
7-1 本章概览 (02:42)

7-2 Dubbo高级特性之异步介绍 (02:20)

7-3 图解Dubbo异步无返回及配置演示 (05:25)

7-4 Dubbo异步无返回源码讲解 (04:29)

7-5 Dubbo异步配置演示 (03:26)

7-6 Dubbo异步源码讲解及问题剖析 (09:36)

7-7 Dubbo异步请求响应映射源码讲解 (04:51)

7-8 Dubbo异步转同步源码讲解 (03:03)

7-9 Dubbo高级特性之事件通知配置演示 (08:27)

7-10 Dubbo高级特性之事件通知源码解析 (10:38)

7-11 Dubbo 消费者异步的小tips (03:22)

7-12 Dubbo 服务提供者异步概念 (02:43)

7-13 图解Dubbo 服务提供者异步 (04:36)

7-14 Dubbo服务提供者异步配置演示 (07:17)

7-15 Dubbo服务提供者异步源码讲解 (07:02)

7-16 Dubbo高级特性之隐式参数传递介绍 (02:54)

7-17 图解Dubbo隐式参数传递 (04:40)

7-18 Dubbo隐式参数源码讲解 (03:08)

7-19 Dubbo高级特性之服务分组和版本讲解 (03:17)

7-20 Dubbo服务分组配置演示 (07:13)

7-21 Dubbo服务版本配置演示 (04:45)

7-22 Dubbo服务分组和服务版本源码解析 (08:33)

7-23 Dubbo服务分组和版本实际项目使用情况介绍 (04:59)

7-24 本章小结 (04:52)


### 第8章 Apache Dubbo 3 的“厚黑之道”，Dubbo 核心功能之集群管理

#### Apache Dubbo 的集群管理是 Dubbo 核心功能之一，提供了包括集群缓存、负载均衡、失效服务剔除等多项重要内容，本章节就带领大家学习 Apache Dubbo 的集群管理。
8-1 本章概览 (01:18)

8-2 Apache Dubbo 负载均衡介绍 (06:27)

8-3 图解Apache Dubbo负载均衡 (02:23)

8-4 构建Apache Dubbo伪集群开发环境上 (07:50)

8-5 构建Apache Dubbo伪集群开发环境下 (06:25)

8-6 Apache Dubbo伪集群效果演示 (07:39)

8-7 Apache Dubbo高级特性之负载均衡配置演示 (02:31)

8-8 RandomLoadBalance源码解析 (10:58)

8-9 RoundRobinLoadBalance源码解析 (09:09)

8-10 LeastActiveLoadBalance源码解析 (05:12)

8-11 ShortestResponseLoadBalance源码解析 (05:11)

8-12 weight和warmup配置示例 (03:48)

8-13 源码讲解负载均衡执行流程 (10:52)

8-14 源码讲解Directory执行流程 (11:23)

8-15 Apache Dubbo集群之route环境准备 (05:02)

8-16 Apache Dubbo集群之route配置演示 (06:08)

8-17 源码讲解ConditionRouter初始化规则 (14:51)

8-18 源码讲解ConditionRouter过滤过程 (09:14)

8-19 Apache Dubbo集群之Cluster配置演示 (02:55)

8-20 源码讲解FailfastClusterInvoker运行原理 (02:55)

8-21 源码讲解FailsafeClusterInvoker运行原理 (02:56)

8-22 源码讲解FailoverClusterInvoker运行原理 (06:12)

8-23 源码讲解FailoverClusterInvoker运行原理 (04:31)

8-24 Apache Dubbo执行流程知识图谱串讲 (05:11)

8-25 本章小结 (03:00)


### 第9章 Apache Dubbo 3 的“七窍玲珑心”，Dubbo 核心功能之扩展点

#### Apache Dubbo 的扩展点管理是Dubbo作为优秀框架的重要组成部分，正是由于扩展点才使得 Dubbo 具有非常良好的兼容性和延展性，本章节就与大家一起学习 Dubbo 的扩展点。
9-1 本章概览 (01:39)

9-2 API和SPI概述 (03:23)

9-3 准备JDK的SPI演示环境 (04:28)

9-4 JDK的SPI演示 (05:19)

9-5 Apache Dubbo SPI概述 (02:21)

9-6 源码讲解getExtensionLoader实现原理 (06:31)

9-7 源码讲解getAdaptiveExtension()实现原理 (09:40)

9-8 源码讲解loadDirectory()实现原理 (19:46)

9-9 源码讲解createAdaptiveExtensionClass实现原理 (09:47)

9-10 源码讲解getExtension实现原理 (08:37)

9-11 源码讲解Apache Dubbo IoC实现 (09:29)

9-12 源码讲解Apache Dubbo AOP实现 (08:59)

9-13 源码讲解Apache Dubbo 动态编译原理 (15:56)

9-14 本章小结 (03:15)


### 第10章 Apache Dubbo 3 的“爱恨情仇”，新特性分析

#### 本章节主要与大家一起了解 Apache Dubbo 3 的新特性一览，并根据新特性总结Dubbo 的发展方向。
10-1 本章概览 (03:10)

10-2 Apache Dubbo 3 新特性速览 (04:19)

10-3 应用级服务发现讲解 (05:51)

10-4 Triple与Dubbo协议讲解 (07:56)

10-5 云原生概念及云原生支持 (05:06)

10-6 Apache Dubbo 3 发展方向预测 (11:36)

10-7 Apache Dubbo 3 配置模板讲解 (10:06)

10-8 本章小结 (04:40)


[下载地址](https://51xueit.vip "下载地址")
