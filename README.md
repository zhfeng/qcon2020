# 下一代面向云原生的编程框架Quarkus

随着各种开放云平台的出现，使得微服务应用的大规模部署成为企业的生产实践，为企业应用提供高可用，高性能和快速迭代能力的同时，也对应用开发人员提出了更高的要求。传统的基于Java和J2EE的编程模型和框架，在云环境里面不再适应，高内存需求和启动速度缓慢也限制了在云平台的扩展能力。对于云原生的编程框架需求也是越来越多，而红帽的[Quarkus](https://quarkus.io)正是积累了在中间件平台数十年的研发经验，精心为开发人员设计和打造的云原生编程框架。专门针对云计算应用，进行了大量的优化和改进，为云计算应用的大规模部署提供最佳实践。这次演讲主要介绍Quarkus框架设计和特点，如何利用Quarkus进行应用开发，如何利用Native模式在云平台进行部署。

## 内容大纲
1. Quarkus框架简介
   * 面向云原生的设计理念
   * 更低的内存需求和更快速的启动时间
   * Native模式
   * Quarkus是如何利用[Graavl Substrate VM](https://github.com/oracle/graal/blob/master/substratevm/README.md)
2. 如何利用Quarkus进行开发
   * 基于JAX-RS的Hello World应用开发和测试演示
   * 开发模式(Development Mode)
   * 如何构建Native应用
3. 容器化和云平台部署
   * 如何构建docker image
   * 如何通过kerbutenes进行应用部署
4. 更多
   * Quarkus的项目进展和路线图
   * 红帽的开放混合云策略(Open Hybrid Cloud Strategy)
   
## 听众受益
* 了解云原生编程框架Quarkus的技术特点和开发实践
* 学习利用Quarkus构建Native应用并在云平台部署
* 了解红帽中间件产品的最新进展

## 适合人群
* 有一定的服务端开发经验的Java开发者
* 对云原生应用感兴趣的开发者
