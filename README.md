#### 涉及内容

-Spring Boot

-Spring MVC

-MyBatis

-MySql, H2

-Flyway

-Heroku

-Git/Github

-Maven

-Restful

#### 创建项目

Spring Initializr

#### 目录结构

src目录：

- src/main/java：程序开发以及主程序入口
- src/main/resources：配置文件
- src/test/java：测试程序

com.example.myproject 建议的目录结构：

- Application.java，建议放到根目录下面，是项目的启动类，Spring Boot 项目只能有一个 main() 方法；
- comm 目录建议放置公共的类，如全局的配置文件、工具类等；
- model 目录主要用于实体（Entity）与数据访问层（Repository）；
- repository 层主要是数据库访问层代码；
- service 层主要是业务类代码；
- web 层负责页面访问控制。

resources 建议的目录结构：

- static 目录存放 web 访问的静态资源，如 js、css、图片等；
- templates 目录存放页面模板；
- application.properties 存放项目的配置信息。

