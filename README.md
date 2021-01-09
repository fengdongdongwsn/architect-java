# :star:《java小白到架构师技术图谱》

**本文整理于github上各大star大神仓库。并根据自己的理解重新进行了整理**

> **本文持续更新中**
>
> 本文收录于https://github.com/fengdongdongwsn/architect-java

## 一、计算机基础

### 1、数据结构

#### （1）基本数据结构

- 数据结构基本概念（时间复杂度和空间复杂度的计算方法）
- 数组
- 链表
- 集合
- 队列
- 栈
- 关联数组
- 跳表
- 倒排索引
- BitSet

#### （2）树

- 二叉树
- 平衡二叉树
- 完全二叉树
- 哈弗曼树
- 二叉查找树
- B、B+、B*树
- LSM树
- 字典树
- 红黑树
- 线段树

#### （3）图

- 最小生成树
- 最短路径算法
- 拓扑排序
- 深搜和广搜

#### （4）排序算法

- 选择排序
- 冒泡排序
- 插入排序
- 快速排序
- 归并排序
- 希尔排序
- 基数排序
- 计数排序
- 桶排序
- 堆排序
- 排序算法使用场景特点总结

#### （5）查找算法

- 顺序查找
- 二分查找
- 插值查找
- 斐波那契查找
- 树表查找

#### （6）常见算法

- KMP算法
- 贪心算法
- 回溯算法
- 剪枝算法
- 动态规划
- 并查集
- 朴素贝叶斯
- 递归算法
- 符号表
- 布隆过滤器

### 2、计算机网络

#### （1）协议

- OSI七层协议
- TCP/IP协议
- HTTP协议

#### （2）网络模型

- 阻塞式IO
- 非阻塞式IO
- 复用IO
- 信号驱动IO
- 异步IO
- Epoll模型
- javaNIO
- javaAIO
- kqueue

#### （3）序列化

- java序列化
- protoBuf
- protoStuff
- avro
- Hessian

### 3、操作系统

#### （1）基本知识

- 操作系统的四个特征
- 操作系统的功能

#### （2）进程与线程

- 进程的概念与分类
- 线程的概念与分类
- 进程与线程的区别
- 进程的状态转换
- CPU调度算法
- 管程
- 协程
- 进程间的通信方式
- 进程间同步问题
  - 生产者消费者问题
  - 哲学家就餐问题
  - 读者-写者问题
  - 锁死的四个必要条件
  - 死锁处理

#### （3）内存管理

- 段式管理
- 页式管理
- 段页式管理
- 页面调度算法

#### （4）其他

- 虚拟内存和逻辑内存

- 静态链接和动态链接
- 缓存
- 僵尸进程与孤儿进程

## 二、java基础

### 1、面向对象基础

- 继承
- 封装
- 多态
- 接口
- 抽象类

### 2、java集合

- 总体框架
- Collection
- ArrayList
- LinkedList
- Vector
- Stack
- 快速失败和快速安全
- HashMap
- TreeMap
- LinkedHashMap
- HashSet
- TreeSet
- Hashtable
- WeakHashMap

### 3、关键字和类

- transient
- instanceof
- static
- this
- super
- void
- final
- String
  - String为什么不可变
  - String、StringBuilder、StringBuffer区别
  - String到底新建了几个对象

### 4、java高级特点

- 注解
- 反射
- 泛型
- 异常
- 枚举
- IO机制
- 编码转换
- java8新特性
- java11新特性

### 5、并发库

#### （1）并发基础

- Thread生命周期
- 线程安全问题
- 线程通信模式
- sleep和wait的区别
- ThreadLocal

#### （2）原子特性

- AtomicInteger
- AtomicBoolean
- AtomicStampedReference
- Unsafe
- CAS

#### （3）并发工具

- CountDownLatch
- CylicBarrier
- Semaphore
- Exchanger
- Phaser
- ForkJoin

#### （4）锁机制

- synchronized
- volatile
- Reentrantlock
- ReenReadWriteLock
- StampedLock
- 公平锁和非公平锁
- 悲观锁和乐观锁
- ABA问题
- 互斥锁和共享锁
- 可重入锁和不可重入锁
- AQS机制
- RingBuffer
- 锁升级
- 锁消除
- 锁粗化

#### （5）并发容器

- ConcurrentHashMap
- ConcurrentSkipListMap
- ConcurrentSkipSet
- ConcurrentLinkedQueue
- CopyOnWriteArrayList
- 阻塞队列
- 优先级队列

#### （6）线程池

- 线程池的几种状态切换
- 线程池的参数
- 线程池的启动流程
- 线程池的分类
- 线程池的大小设置

### 6、JVM

- java内存结构（jdk1.7和1.8）
- 垃圾回收机制
- 类加载机制
- 内存分类和回收
- 四种引用（强、软、弱、虚）
- 内存溢出
- JVM调优工具
- 垃圾回收器
- ZGC的认识
- JNI
- 内存逃逸

## 三、必备基础

### 1、设计模式

- 创建型模式
- 结构性模式
- 行为性模式
- 设计模式的六种原则
- MVC模型
- MVVC模型
- UML
- 康威定理

### 2、Linux

- Linux目录结构
- 常见命令
- 文件系统管理
- 用户系统管理
- 进程管理
- 网络管理
- 备份与恢复
- 文本文件处理命令
- shell编程

### 3、代码工具

- Git
- Maven
- gradle
- 日志框架
- Junit

## 四、数据库

### 1、mysql

#### （1）基本知识

- 三大范式
- 数据库、数据表、字段的增删改查基本操作
- 分区表
- 视图
- 外键约束
- 游标
- 变量
- 存储过程
- 函数
- 字符集

#### （2）存储引擎

- InnoDB
- MyISAM
- 转换表的引擎

#### （3）事务

- 隔离级别
- 多版本并发工具
- 分布式事务
- ACID特性

#### （4）索引

- 聚集索引
- 非聚集索引
- 复合索引
- 底层实现原理

#### （5）锁

#### （6）测试

#### （7）优化方案

- 数据类型优化
- 索引优化
- 查询性能优化
- mysql配置优化
- 硬件优化

#### （8）高可用方案

#### （9）复制迁移

### 2、Redis

- 持久化机制
- 缓存三种问题（穿透、击穿、雪崩）
- 内存淘汰策略
- 哨兵机制
- 集群方案
- 复制原理

### 3、MongoDB

### 4、Hbase

## 五、常用基本框架

### 1、servlet

### 2、Spring系列家族

### 3、Mybatis

### 4、JPA

### 5、Netty

### 6、websocket

## 六、运维统计相关

### 1、平台监控

- zabbix、Nagios、Ganglia等
- Linux命令监控：top、sar、tsar、nload等
- JVM监控工具

### 2、APM

### 3、持续集成

- 持续集成工具Jenkins
- TeamCity
- Travis CI
- GitLab CI
- 环境分离

### 4、容器相关

- Docker
- K8S

### 5、虚拟化

- KVM
- Xen
- OpenVZ

### 6、自动化运维

- Ansible
- puppet
- chef

### 7、测试

- 单元测试
- 压力测试
- 灰度测试
- A/B测试
- 蓝绿测试
- TDD测试理论
- 全链路测试

## 七、中间件

### 1、web

- Nginx
- OpenRestry
- Tengine
- ApacheHttpd

### 2、服务器

- Tomcat
- Jetty
- WebLogic
- JBoss

### 3、缓存

- 本地缓存
- 客户端缓存
- web缓存
- Memcached
- Redis
- Tair
- cellar

### 4、消息队列

- Kafka
- ActiveMQ
- RocketMQ
- RabbitMQ
- Redis消息队列
- ZeroMQ

### 5、RPC

- Dubbo
- Thrift
- gRPC
- java的RMI

### 6、定时任务

- Quartz
- cron定时调度
- java定时任务
- Elastic-job
- opencron
- LTS

### 7、数据库中间件

- Mycat
- Sharding Jdbc

### 8、搜索引擎

- Lucene
- Elasticsearch
- Solr
- sphinx

## 八、微服务

## 1、微服务框架

- Springcloud
- SpringCloud Alibaba
- Dropwizard
- Akka

### 2、注册中心

- Eureka
- Zookeeper
- Consul

### 3、服务调用

- Feigh
- restTemplete

### 4、负载均衡

- Ribbon

### 5、网关

- Gateway
- kong
- zuul

### 6、配置中心

- Zookeeper
- Apollo
- Springcloud Config

### 7、链路跟踪

- SpringCloud Bus
- SpringCloud Sleuth
- Zipkin
- Dapper
- log-based
- HTrace

## 九、分布式

### 1、分布式理论

- CAP理论
- BASE理论
- 幂等性
- 分布式锁
  - redis实现
  - 数据库实现
  - Zookeeper实现

### 2、一致性算法

- Paxos
- ZAB
- Raft
- Gossip
- 两阶段提交协议
- 节点选举策略
- 一致性hash算法

### 3、分布式文件系统

- HDFS
- fastDFS

### 4、分布式ID

- Snowflake算法
- Flicker算法
- UUID
- MongoDB实现

### 5、分布式事务

- 多阶段提交
- TCC补偿事务
- 本地消息表
- MQ事务消息
- 最大努力通知

### 6、稳定性高可用方案

- 软硬件负载均衡
- 限流
- 容灾
- 平滑启动

## 十、安全

### 1、web安全

- XSS
- CRSF
- SQL注入
- DDOS
- DNS攻击
- 脚本注入
- 序列化攻击
- 中间人攻击

### 2、加密解密算法

- 对称加密
- 非对称加密
- hash算法
- 数字签名
- Base64

### 3、框架

- Shiro
- SpringSecurity

### 4、授权认证

- RBAC
- OAuth2.0
- OIDC
- SAML
- TLS全链路加密
- JWT用户认证
- Check前置检查
- Quota配额管理
- Telemetry遥测报告
- 双因素认证（2FA）
- 单点登录SSO

## 十一、项目管理

### 1、开发设计

- DDD领域驱动模型
- Actor模式
- 响应式编程
- DODAF2.0
- Serverless
- Service Mesh

### 2、项目管理

- 代码规范
- 敏捷开发
- 极限编程
- 结对编程
- RUP
- SCRUM
- PDCA循环质量管理
- FMEA管理模式

### 3、架构管理

- DevOps
- OpenGroup
- ABSD架构方法论
- 架构设计原则
- 异地多活
- Knative弹性伸缩

## 十二、大数据云计算

### 1、流式计算

- storm
- Flink
- KafkaStream

### 2、Hadoop

- HDFS
- MapReduce
- Yarn
- Spark

## 十三、开发工具

- IDEA
- VSCode
- VIM
- Gitlab
- Navicat
- XShell
- postman
- Filezilla
- Fiddler

## 十四、软实力

- 项目管理
- 团队管理
- 个人素养提升
- 职业素养提升
- 英语

## 十五、学习资源

### 1、视频网站

- [B站](https://www.bilibili.com/)
- [慕课网](https://www.imooc.com/)
- [中国大学MOOC网](https://www.icourse163.org/category/all)

### 2、博客社区

- [CSDN](https://www.csdn.net/)
- [开源中国](https://www.oschina.net/)
- [简书](https://www.jianshu.com/)
- [思否](https://segmentfault.com/)
- [掘金](https://juejin.cn/)
- [博客园](https://www.cnblogs.com/)
- [阿里云社区](https://developer.aliyun.com/)
- [开发者头条](https://toutiao.io/)
- Medium

### 3、技术手册

- [W3Cschool](https://www.w3cschool.cn/)
- [Runoob.com](https://www.runoob.com/)
- [慕课网教程手册](http://www.imooc.com/wiki/)

### 4、行业资讯

- [知乎](https://www.zhihu.com/)
- [stackoverflow](https://stackoverflow.com/)

### 5、代码托管

- [github](https://github.com/)
- [gitee](https://gitee.com/)
- [coding](https://coding.net/)

### 6、电子书网站

- [gitbook](https://www.gitbook.com/)
- [aibooks](https://www.aibooks.club/)
- [书栈网](https://www.bookstack.cn/)
- [搬书匠](http://www.banshujiang.cn/)
- [鸠摩搜索](https://www.jiumodiary.com/)
- [IT-ebooks国外免费](https://it-ebooks.info/)

### 7、程序员交流网站

- [V2EX](https://www.v2ex.com/)

### 8、云服务器

- [阿里云](https://www.aliyun.com/)
- [腾讯云](https://cloud.tencent.com/)
- [百度云](https://cloud.baidu.com/)
- [华为云](https://www.huaweicloud.com/)
- [七牛云](https://www.qiniu.com/)
- [西部数据](https://www.west.cn/)
- [金山云](https://www.ksyun.com/)

### 9、面试刷题

- [LinkCode](http://www.linkedcode.com/)
- [LeetCode](https://leetcode-cn.com/)
- [牛客网](https://www.nowcoder.com/)

### 10、找工作

- [100offer](http://www.cfenews.com/100offerwang/)
- [拉勾网](https://www.lagou.com/)

### 11、数据资源下载

- [国家数据](https://data.stats.gov.cn/easyquery.htm?cn=A01)
- [MSDN](https://msdn.itellyou.cn/)
- [PUDN](http://www.pudn.com/)
- [OPSX阿里巴巴开源镜像](http://www.pudn.com/)
- T[UNA清华开源软件](https://mirrors.tuna.tsinghua.edu.cn/)
- [163网易开源镜像](http://mirrors.163.com/)

### 12、编程外包

- [大神部落](http://www.buluo007.com/)
- [程序员客栈](https://www.proginn.com/)
- [码市](https://codemart.com/)
- [开源众包](https://zb.oschina.net/)

## 十六、综合类网站

- [法律法规](http://www.gov.cn/flfg/)
- [身体健康](http://www.9ask.cn/souask/q/q3113193.htm)
- [中华人民共和国职业病防治法](https://duxiaofa.baidu.com/detail?searchType=statute&from=aladdin_28231&originquery=%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E8%81%8C%E4%B8%9A%E7%97%85%E9%98%B2%E6%B2%BB%E6%B3%95&count=88&cid=a1852015fa9454ed1e1276accc200a28_law)

> 本文持续更新中
>
> 本文收录于https://github.com/fengdongdongwsn/architect-java

![](https://s3.ax1x.com/2020/12/18/rJnbO1.jpg)

















