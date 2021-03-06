# moreco

## 项目介绍 

### 更多功能及文档正在不断完善中……
### 演示地址 [https://moreco.weechang.xyz/](https://moreco.weechang.xyz/)
### 使用文档 [https://moreco-doc.weechang.xyz/](https://moreco-doc.weechang.xyz/)

moreco -- more ecosystem 更完全的生态系统

moreco 是一个能够为小、中、大型项目提供最合适架构的一条龙生态系统。满足项目从小型到中型至大型的衍变过程。从编码到监控至运维都满足、且各种功能都插件化，支持插件间的切换。

常常在网上看到很多项目，一来就是spring cloud、docker等。当时一个项目最开始可能只是一个简单的想法，而这个想法需要快速成型。所以微服务、容器化并不合适，反而一个简单的单体应用就够了。

但是很少有从单体到集群再到微服务的项目。这样可能开始的时候单体项目是一套代码体系、微服务的时候又是另一套代码体系。这样对开发资源造成很大的浪费。

moreco能够满足你的项目从单体到微服务的整个流程。但你从单体迁移到微服务的时候，只需要改动很小一部分代码就能实现项目的微服务化，从而节省项目迁移成本。

moreco不仅仅是一套开发框架，moreco更是一套生态系统。从开发到监控至运维，moreco都提供一套更为完善的组件支持。包括但不限于以下项目：

* 架构方面：spring boot开发、spring cloud开发、领域驱动开发。

* 开发方面：对象存储（七牛、阿里云、腾讯云、又拍云、LOCAL）、消息通知（邮件、短信、站内信）。

* 监控报警：物理机监控、应用监控、方法监控、数据库监控。

* 运维方面：统一日志。

## 软件架构

软件架构说明

## 技术选型

### 后端技术

| **技术**                    | **名称**       | **官网**  |
| -------------------------- | -------------- | --------  |
| Spring Framework           | 容器            | [https://spring.io/projects/spring-framework](https://spring.io/projects/spring-framework) |
| Spring MVC                 | MVC框架         |  |
| Spring Boot                | 快速开发        | [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot) |
| Spring Data                | 持久化框架       | [https://spring.io/projects/spring-data](https://spring.io/projects/spring-data) |
| Apache Shiro               | 安全框架        | [http://shiro.apache.org/](http://shiro.apache.org/)  |
| Swagger2                   | 接口文档        | [http://swagger.io/](http://swagger.io/) |
| AliOSS & Qiniu & QcloudCOS | 云存储平台       | [https://www.aliyun.com/product/oss/](https://www.aliyun.com/product/oss/) [http://www.qiniu.com/](http://www.qiniu.com/) [https://www.qcloud.com/product/cos](https://www.qcloud.com/product/cos) |
| Jenkins                    | 持续集成工具     | [https://jenkins.io/index.html](https://jenkins.io/index.html) |
| Maven                      | 版本控制工具     | [http://maven.apache.org/](http://maven.apache.org/) |

### 前端技术

| **技术**      | **名称**       | **官网**  |
| --------------| --------------| --------  |
| Node.js       | 编译环境       | [https://nodejs.org/](https://nodejs.org/) |
| npm           | 版本控制工具   | [https://www.npmjs.com/](https://www.npmjs.com/) |
| Vue.js        | 组件库         | [https://cn.vuejs.org/](https://cn.vuejs.org/) |
| iView         | UI组件库       | [https://www.iviewui.com/](https://www.iviewui.com/) |
| iView Admin   | 界面框架       | [https://lison16.github.io/iview-admin-doc/#/](https://lison16.github.io/iview-admin-doc/#/)  |


## 项目结构
``` 
moreco
├── moreco-base ------------------------------ 基础、公共方法封装
├── moreco-cloud ----------------------------- spring cloud 组件
|    ├── moreco-cloud-breaker----------------- 熔断
|    ├── moreco-cloud-config  ---------------- 配置中心
|    ├── moreco-cloud-gateway ---------------- 网关
|    ├── moreco-cloud-register --------------- 服务注册中心
├── moreco-demo ------------------------------ demo
|    ├── moreco-spring-boot-demo ------------- spring boot demo
├── moreco-message --------------------------- 消息中心
├── moreco-monitor --------------------------- 监控中心
├── moreco-ops ------------------------------- 运维中心
├── moreco-oss ------------------------------- 对象存储
├── moreco-rbac ------------------------------ RBAC权限管理
├── moreco-security -------------------------- 安全认证
|    ├── moreco-security-base ---------------- 安全认证基础组件
|    ├── moreco-security-shiro --------------- shiro 组件
|    ├── moreco-security-spring-security ----- spring security 组件
├── moreco-starter --------------------------- 启动组件
|    ├── moreco-starter-spring-boot ---------- spring boot 启动组件
|    ├── moreco-starter-spring-cloud --------- spring cloud 启动组件
```

## 运行效果

![Login](/doc-of-project/moreco-login.png)

![Home](/doc-of-project/moreco-home.png)

![Rbac](/doc-of-project/moreco-rbac.png)

![i18n](/doc-of-project/moreco-i18n.png)

![swagger](/doc-of-project/moreco-swagger.png)

![monitor](/doc-of-project/moreco-monitor.png)

## 开发进度

## 安装教程
1. xxxx
2. xxxx
3. xxxx

## 使用说明

1. xxxx
2. xxxx
3. xxxx

## QQ交流群

[493659743](https://jq.qq.com/?_wv=1027&k=5Czuxq5)