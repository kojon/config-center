# config-center

#### 项目说明

spring cloud配置中心

#### 参考文档

spring官网：

首页：https://spring.io/projects/spring-cloud-config

手册：https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.1.1.RELEASE/single/spring-cloud-config.html

#### 项目文档说明

请参考文档中注释

#### 提示

yaml(yml) 特殊符号---说明

--- 可以在同一个文件中，使用---表示一个文档的开始。代表定义了两个profile，一个是dev，一个test；

```yaml
---
# dev环境
spring:
  application:
    name: config-dev
  profiles: dev

---
# test环境
spring:
  application:
    name: config-test
  profiles: test
```





