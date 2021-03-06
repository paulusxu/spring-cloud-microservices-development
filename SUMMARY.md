# 目录

* [内容简介](docs/Introduction.md)
* [前言](docs/Preface.md)
* [第1章 微服务概述](docs/ch1/1.md)
    * [1.1 传统软件行业面临的挑战](docs/ch1/1-1.md)
    * [1.2 常见分布式系统架构](docs/ch1/1-2.md)
    * [1.3 单块架构如何进化为微服务架构](docs/ch1/1-3.md)
    * [1.4 微服务架构的设计原则](docs/ch1/1-4.md)
    * [1.5 如何来设计微服务系统](docs/ch1/1-5.md)
* [第2章 微服务的基石——Spring Boot](docs/ch2/2.md)
    * [2.1 Spring Boot 简介](docs/ch2/2-1.md)
    * [2.2 开启第一个 Spring Boot 项目](docs/ch2/2-2.md)
    * [2.3 Hello World](docs/ch2/2-3.md)
    * [2.4 如何搭建开发环境](docs/ch2/2-4.md)
    * [2.5 Gradle 与 Maven 的抉择](docs/ch2/2-5.md)
* [第3章 Spring Boot 的高级主题](docs/ch3/3.md)
    * [3.1 构建 RESTful 服务](docs/ch3/3-1.md)
    * [3.2 Spring Boot 的配置详解](docs/ch3/3-2.md)
    * [3.3 内嵌 Servlet 容器](docs/ch3/3-3.md)
    * [3.4 实现安全机制](docs/ch3/3-4.md)
    * [3.5 允许跨域访问](docs/ch3/3-5.md)
    * [3.6 消息通信](docs/ch3/3-6.md)
    * [3.7 数据持久化](docs/ch3/3-7.md)
    * [3.8 实现热插拔（hot swapping）](docs/ch3/3-8.md)
* [第4章 微服务的测试](docs/ch4/4.md)
    * [4.1 测试概述](docs/ch4/4-1.md)
    * [4.2 测试的类型和范围](docs/ch4/4-2.md)
    * [4.3 如何进行微服务的测试](docs/ch4/4-3.md)
* [第5章 微服务的协调者——Spring Cloud](docs/ch5/5.md)
    * [5.1 Spring Cloud 简介](docs/ch5/5-1.md)
    * [5.2 Spring Cloud 入门配置](docs/ch5/5-2.md)
    * [5.3 Spring Cloud 的子项目介绍](docs/ch5/5-3.md)
* [第6章 服务拆分与业务建模](docs/ch6/6.md)
    * [6.1 从一个天气预报系统讲起](docs/ch6/6-1.md)
    * [6.2 使用Redis提升应用的并发访问能力](docs/ch6/6-2.md)
    * [6.3 实现天气数据的同步](docs/ch6/6-3.md)
    * [6.4 给天气预报一个“面子”](docs/ch6/6-4.md)
    * [6.5 如何进行微服务的拆分](docs/ch6/6-5.md)
    * [6.6 领域驱动设计与业务建模](docs/ch6/6-6.md)
* [第7章 天气预报系统的微服务架构设计与实现](docs/ch7/7.md)
    * [7.1 天气预报系统的架构设计](docs/ch7/7-1.md)
    * [7.2 天气数据采集微服务的实现](docs/ch7/7-2.md)
    * [7.3 天气数据API微服务的实现](docs/ch7/7-3.md)
    * [7.4 天气预报微服务的实现](docs/ch7/7-4.md)
    * [7.5 城市数据API微服务的实现](docs/ch7/7-5.md)
* [第8章 微服务的注册与发现](docs/ch8/8.md)
    * [8.1 服务发现的意义](docs/ch8/8-1.md)
    * [8.2 如何集成 Eureka Server](docs/ch8/8-2.md)
    * [8.3 如何集成 Eureka Client](docs/ch8/8-3.md)
    * [8.4 实现服务的注册与发现](docs/ch8/8-4.md)
* [第9章 微服务的消费](docs/ch9/9.md)
    * [9.1 微服务的消费模式](docs/ch9/9-1.md)
    * [9.2 常见微服务的消费者](docs/ch9/9-2.md)
    * [9.3 使用 Feign 实现服务的消费者](docs/ch9/9-3.md)
    * [9.4 实现服务的负载均衡及高可用](docs/ch9/9-4.md)
* [第10章 API 网关](docs/ch10/10.md)
    * [10.1 API 网关的意义](docs/ch10/10-1.md)
    * [10.2 常见 API 网关的实现方式](docs/ch10/10-2.md)
    * [10.3 如何集成Zuul](docs/ch10/10-3.md)
    * [10.4 实现 API 网关](docs/ch10/10-4.md)
* [第11章 微服务的部署与发布](docs/ch11/11.md)
    * [11.1 部署微服务将面临的挑战](docs/ch11/11-1.md)
    * [11.2 持续交付与持续部署微服务](docs/ch11/11-2.md)
    * [11.3 基于容器的部署与发布微服务](docs/ch11/11-3.md)
    * [11.4 使用 Docker 来构建、运行、发布微服务](docs/ch11/11-4.md)
* [第12章 微服务的日志与监控](docs/ch12/12.md)
    * [12.1 微服务日志管理将面临的挑战](docs/ch12/12-1.md)
    * [12.2 日志集中化的意义](docs/ch12/12-2.md)
    * [12.3 常见日志集中化的实现方式](docs/ch12/12-3.md)
    * [12.4 Elastic Stack 实现日志集中化](docs/ch12/12-4.md)
* [第13章 微服务的集中化配置](docs/ch13/13.md)
    * [13.1 为什么需要集中化配置](docs/ch13/13-1.md)
    * [13.2 使用 Config 实现的配置中心](docs/ch13/13-2.md)
* [第14章 微服务的高级主题——自动扩展](docs/ch14/14.md)
    * [14.1 什么是自动扩展](docs/ch14/14-1.md)
    * [14.2 自动扩展的意义](docs/ch14/14-2.md)
    * [14.3 自动扩展的常见模式](docs/ch14/14-3.md)
    * [14.4 如何实现微服务的自动扩展](docs/ch14/14-4.md)
* [第15章 微服务的高级主题——熔断机制](docs/ch15/15.md)
    * [15.1 什么是服务的熔断机制](docs/ch15/15-1.md)
    * [15.2 熔断的意义](docs/ch15/15-2.md)
    * [15.3 熔断与降级的区别](docs/ch15/15-3.md)
    * [15.4 如何集成 Hystrix](docs/ch15/15-4.md)
    * [15.5 实现微服务的熔断机制](docs/ch15/15-5.md)
* [第16章 微服务的高级主题——分布式消息总线](docs/ch16/16.md)
    * [16.1 什么是消息总线](docs/ch16/16-1.md)
    * [16.2 Spring Cloud Bus 设计原理](docs/ch16/16-2.md)
    * [16.3 如何集成 Bus](docs/ch16/16-3.md)
    * [16.4 实现配置信息的自动更新](docs/ch16/16-4.md)
* [附录A：本书所涉及到的技术及相关版本](docs/appendices/appendices-a.md)
* [参考资料](docs/references.md)

