# JavaThousandQ（Java面试千问）
* 这里只有问题，没有答案
* 一个好问题比一个好答案更重要
* 这里都是实际在Java面试中出现过或者某些面试官YY的面试问题，答案大家可以直接去DeepSeek、豆包、元宝、ChatGPT等查询。

# Java基础

## JVM
* 说几个你用的比较熟的垃圾收集器及其核心过程

## JMM
* 说说什么是JMM（Java Memory Model）？它用来解决什么问题？


## 并发&多线程
### 虚拟线程
* 虚拟线程和普通线程有什么区别？它用来解决什么问题？
* 有了虚拟线程，是不是响应式编程就没有用武之地了？
* 说说什么是AQS？它里面用到了什么数据结构？

## 响应式编程
* 响应式编程的定义是什么？

# 网络 & IO
* IO的线程模型有哪几种？

# 一致性算法


## 通用
* 为什么很多中间都要【选主】？（要选主的本质是什么？）

## Raft

## Gossip

## Paxos


# Spring
* Spring的事务传播途径有哪些？
* 在Spring中使用事务有哪些注意事项？

## Spring Web & Spring Web MVC & Spring WebFlux
* Spring WebFlux + Servlet3.0 和 Spring Web MVC + Servlet3.1 效果上有什么区别？哪个会更好？



# NoSQL
## Redis
* Redis Sorted Set是如何实现的？底层用的是什么数据结构？
* Redis集群部署有哪几种方式？
* Redis Cluster和Redis Sentinel的区别是什么？各自有哪些适合使用的场景?
* Redis中Hash结构如果Field很多会带来哪些问题？
* Redis的数据持久化有哪些方式？各自的特点是什么？
* 如何用Redis来实现分布式锁？
* Redisson的RLock实现原理是什么？
* 如何使用Redis做缓存？

## Elasticsearch
* Elasticsearch和Lucene是什么关系？
* Elasticsearch是强一致性的吗？
* Elasticsearch能自动扩容吗？


## MongoDB
* MongoDB是强一致性的吗？
* MongoDB有全文索引（Text Indexes），那还要Elasticsearch干啥？
* 哪些场景适合使用MongoDB，哪些场景适合使用Elasticsearch？

# MySQL
* MySQL有哪几种事务隔离级别？
* MySQL有哪几种日志？分别的作用是什么？

# MQ
## Kafka

## RocketMQ
* RocketMQ的核心组件有哪些？各自的职责是什么？
* RocketMQ消费消息有哪些模式？分别适合哪些场景来使用？
* RocketMQ的Message Queue是什么？
* RocketMQ的顺序消息如何实现？
* RocketMQ合理设置Queue数量？
* RocketMQ与Kafka的核心区别是什么？
* RocketMQ的事务消息的核心流程是什么？
* Rocket如何保证“至少一次”？


# 云计算

# 研发质量
* 作为TL，你如何提升研发团队的研发质量？

# 系统稳定性
* 你觉得应该如何做系统稳定性建设？

# 系统设计
* 如何设计一个秒杀系统？


