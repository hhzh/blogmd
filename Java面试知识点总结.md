---
title: Java面试知识点总结
date: 2017-04-13 11:21:02
tags: Java
---
概要：本篇文章是介绍Java面试常问到的知识点，不能概括面试所有的知识点，只是写了个大概。如果想了解这些知识点的答案或者更多、更深的内容，还是需要认真看Java相关技术书籍。参见我的另一篇文章 [Java开发必看书籍](http://hhzh.github.io/2017/04/12/Java%E5%BC%80%E5%8F%91%E4%B9%A6%E7%B1%8D%E6%8E%A8%E8%8D%90/) 。以下的这些问题都可以在推荐的书籍中找到或总结出答案。
1.  Java基础
1.1 访问权限修饰词的含义
1.2 Object类有哪些方法
1.3 clone方法是浅拷贝还是深拷贝
1.4 static关键字的含义
1.5 值传递和引用传递的区别
1.6 反射的用法
1.7 NIO相比与IO的优点
1.8 Java异常

2.  集合
2.1  hashmap的实现原理
2.2  hashset的实现原理
2.3  hashmap与hashtable的区别
2.4  怎样可以让hashmap变成线程安全
2.5  数组和List集合排序算法的底层实现原理
2.6  迭代器的使用

3. MySQL
3.1 MySQL常见的存储引擎及其优缺点
3.2 分组函数的使用
3.3 查询语句的优化方法
3.4 如何分库分表

4. Spring
4.1 解释IOC、AOP
4.2 Spring事务的传播特性和隔离级别有哪些
4.3 Spring容器的加载顺序
4.4 你看过哪些Spring源码

5. 设计模式
5.1 常见的设计模式有哪些（必须背诵23种设计模式及其应用场景）
5.2 除了3种不常用到的设计模式，必须能手写出20种设计模式

6. 并发多线程
6.1 ThreadLocal的含义
6.2 ConcurrentHashMap的实现原理
6.3 ThreadPoolExecutor的参数列表及其含义和用法
6.4 线程池设置成多大合适，怎样获得CPU的数目
6.5 Synchronized、volatile、CountDownLatch、Semaphore、CyclicBarrier的用法
6.6 Atomic类、FutureTask、ReentrantReadWriteLock的用法
6.7 写出生产者、消费者模式

7. JVM与GC
7.1 Java内存模型及每个区域的作用和存储的东西
7.2 常见的垃圾收集算法有哪些
7.3 常见的垃圾收集器及其作用
7.4 Java是怎么进行垃圾回收的
7.5 类加载过程
7.6 常见JVM调优参数有哪些
7.7 常见的JVM监控的命令工具有哪些
7.8 你遇到过哪些JVM调优案例，是怎么解决的

8. SpringMVC
8.1 SpringMVC的优点及其作用
8.2 前端请求到SpringMVC的处理过程
8.3 SpringMVC如何实现检测用户是否登录

9. Git
9.1 Git的常用命令
9.2 怎样保存工作进度
9.3 怎样回滚到上一次提交
9.4 从创建分支到结束分支的过程

10. Maven
10.1 一个jar包的唯一标识是什么
10.2 maven常用的命令有哪些
10.3 查看maven依赖的命令是什么
10.4 如何解决依赖冲突

11. Mybatis
11.1 Mybatis的用法
11.2 Mybatis常用标签的用法

12. Linux
12.1 Linux的常用命令
12.2 awk、sed命令的用法
12.3 你写过哪些Linux脚本

13. Redis
13.1 Redis的数据结构及对象有哪些
13.2 过期键的处理方法
13.3 怎么实现数据持久化
13.4 你在哪些地方用到Redis，用到Redis的哪些功能，怎么使用的

14. MQ消息队列
14.1 MQ的作用和优点
14.2 mq如何保证消息不丢失
14.3 出现异常后，消息怎么处理
14.4 集群和负载均衡的使用

15. Dubbo
15.1 Dubbo的作用及优点
15.2 dubbo的工作流程
15.3 dubbo的常用配置

16. SpringBoot
16.1 SpringBoot的优点
16.2 SpringBoot和SpringMVC相比优缺点

17. Netty
17.1 Netty的作用和优点

18. Restful架构
18.1 Restful架构风格的作用及优点

19. Nginx
19.1 Nginx的作用及优点
19.2 Nginx的常用配置

20. 计算机网络
20.1 三次握手与四次挥手
