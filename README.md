JeeWeb敏捷开发平台(Mybatis),分布式应用框架
===============
*   QQ交流群： 46417153
*   码云地址：https://gitee.com/huang465265897/jeeweb-mybatis-spring-boot

简介
-----------------------------------
JeeWeb Mybatis版本是一款基于Springboot2.0+dubbo+redis+SpringMVC+Spring+Mybatis+Mybatis Plus的敏捷开发系统；它是一款具有代码生成功能的智能快速开发平台；是以Spring Framework为核心容器，Spring MVC为模型视图控制器，Mybatis为数据访问层， Apache Shiro为权限授权层，Ehcahe对常用数据进行缓存，Disruptor作为并发框架，Bootstrap作为前端框架的优秀 **开源** 系统。

JeeWeb是一款 **全开源开发平台** ，特别 **代码生成器模块也采用开源模式** ，各位开发者可以根据自己的需要改造出更加适合自己的代码生成器，不管是做项目、学习、接私活它都将是你的最佳拍档；

JeeWeb主要定位于企业快速开发平台建设，已内置很多优秀的基础功能和高效的 **代码生成** 工具，包括：系统权限组件、数据权限组件、数据字典组件、核心工具组件、视图操作组件、代码生成、 **UI模版标签** 库等。前端界面风格采用了结构简单、性能优良、页面美观大气的Twitter Bootstrap页面展示框架。采用分层设计、提交数据安全编码、密码加密、访问验证、数据权限验证。使用Maven做项目管理，提高项目的易开发性、扩展性。

目前功能模块代码生成器、权限框架、数据字典、数据缓存、并发框架、数据监控、计划任务、多数据源管理、附件管理、类似mybatis动态SQL、UI模板标签、短信发送、邮件发送、统计功能等功能。

JeeWeb的开发方式采用（ **代码生成器快速设计生成代码->手工完善逻辑->丰富模板标签快速前端开发** ），可以快速协助java开发人员解决60%的重复工作，让开发人员更多关注业务逻辑的实现，框架使用前端模板标签，解放JAVA开发人员的开发压力，提高开发效率，为企业节省项目研发成本，减少开发周期。

JeeWeb 技术特点
-----------------------------------
JeeWeb使用目前流程的WEB开发架构技术，如**Springboot SpringMVC, Mybatis,Apache Shiro, Disruptor , ehcache, Jquery ,BootStrap** 等等，支持多种数据库MySQL, Oracle, sqlserver等。  **分层设计：使用分层设计，分为dao，service，Controller，view层，层次清楚，低耦合，高内聚。**  

安全考虑：严格遵循了web安全的规范，前后台双重验证，参数编码传输，密码md5加密存储，shiro权限验证，从根本上避免了SQL注入，XSS攻击，CSRF攻击等常见的web攻击手段。

JeeWeb 功能特点
-----------------------------------
* 	采用Springboot2.0+SpringMVC+Spring+Mybatis+Mybatis Plus+Shiro+ Ehcache+Disruptor+Jquery + Boostrap + Ztree等基础前后端架构架构
* 	采用面向声明的开发模式， 基于泛型编写极少代码即可实现复杂的数据展示、数据编辑、表单处理等功能，在不使用代码生成器的情况下，也只需要很少的代码就能实现基础的CURD操作，再配合在线开发与代码生成器的使用，更加加快了开发的进度，将J2EE的开发效率成本提高，可以将代码减少60%以上。
* 	在线开发(通过在线配置实现一个表模型的增删改查功能，无需一行代码，支持用户自定义表单布局) 
* 	代码生成器，支持多种数据模型,根据表生成对应的Entity,Service,Dao,Controller,JSP等,增删改查功能生成直接使用
* 	UI标签开发库，针对前端UI进行标准封装表，页面统一采用UI标签实现功能：数据datagrid,treegrid,FileInput,Editor,GridSelect等，实现JSP页面零JS，开发维护简洁高效
* 	查询过滤器：只需前端配置，后台动态拼SQL追加查询条件；支持多种匹配方式（全匹配/模糊查询/包含查询/不匹配查询）
* 	移动平台支持，对Bootstrap(兼容Html5)进行标准封装
* 	国际化（支持多语言，国际化的封装为多语言做了便捷支持）
*   多数据源（在线配置数据源，数据源工作类封装）
* 	数据权限：整合Shiro权限
*   计划任务控制（在线配置计划任务、方便计划任务的时间调整规划）
*   邮件发送（配置邮件模版、邮件帐号的在线配置、邮件异步发送、邮件发送日志功能统计）
*   短信发送（配置短信模版、短信帐号的在线配置、短信异步发送、短信发送日志功能统计、支持短信发送平台动态切换）
*   多种首页风格切换,支持自定义首页风格。（Inspinia风格|ACE风格）
*   数据统计报表：丰富的报表统计功能
* 	支持多种浏览器: Google, 火狐, IE,360 等
* 	支持数据库: Mysql,Oracle10g,SqlServer等
* 	基础权限: 用户，角色，菜单权限
* 	Web容器测试通过的有Jetty和Tomcat,Weblogic
* 	要求JDK1.8+

技术选型
===============

1、后端

* 核心框架：Springboot2.0+dubbo(zookeeper注册中心)+Spring Framework
* 安全框架：Apache Shiro/Spring security + Jwt
* 视图框架：Spring MVC
* 服务端验证：Hibernate Validator
* 布局框架：Beetl+Freemarker
* 任务调度：Quartz/Xxl-job
* 持久层框架：Mybatis
* 数据库连接池：Alibaba Druid
* 缓存框架：Ehcache/Redis/hazelcast
* 并发框架：Disruptor
* 日志管理：SLF4J、Log4j、Logback
* 工具类：Apache Commons、Jackson、Xstream、

2、前端

* JS框架：jQuery。
* CSS框架：Twitter Bootstrap
* 客户端验证：Validform。
* 富文本在线编辑：markdown、simditor、Summernote、CodeMirror自由切换
* 文件上传工具:Bootstrap fileinput
* 数据表格：jqGrid
* 对话框：layer
* 树结构控件：jQuery zTree
* 日期控件： datepicker
* 代码高亮： syntaxhighlighter

简单使用说明
-----------------------------------
* 本项目使用zookeeper-3.4.8、redisbin_x64 环境，启动项目之前需启动该服务,或者通过该地址下载:https://gitee.com/huang465265897/jeeweb-mybatis-spring-boot/attach_files
* 导入sql/jeeweb-mysql-v1.0(xx).sql文件到mysql数据库,根据自己的数据库导入相应的sql文件,数据库中需要创建名为jeeweb_mybatis 的数据库名，导入sql文件格式 utf8格式
* 导入项目到IDEA.
* 修改数据库配置文件dbconfig.properties中的账号密码.
* 启动项目,管理员账号admin/密码123456
* jvm参数优化：http://xxfox.perfma.com


计划任务(微服务框架整合)
-----------------------------------
* 注册发现服务->Nacos
* 熔断降级、系统负载->Sentinel
* API网关->Spring Cloud Gateway
* 其他阿里生态(fescar分布事务、dubbo...)

平台目录结构说明
-----------------------------------
```
x-manerger-sys-common 后台管理系统公用模块
    x-manerger-sys-common-base 基础模块
    x-manerger-sys-common-email 邮件模块
    x-manerger-sys-common-mybatis 数据库操作模块、Mybatis-plus
    x-manerger-sys-common-oss 附件上传模块
    x-manerger-sys-common-quartz 任务模块
    x-manerger-sys-common-query 参数封装模块
    x-manerger-sys-common-security 鉴权模块
    x-manerger-sys-common-sms  短信模块
    x-manerger-sys-common-utils 工具模块
    x-manerger-sys-common-limit 限流模块
    x-manerger-sys-common-lock 分布式锁模块
    x-manerger-sys-common-idgenerator id生成模块
    x-manerger-sys-common-queue 排队模块
x-manerger-sys-service 后台管理模块
x-restful 业务系统模块
x-micro-service 微服务模块(计划中...)
```
系统演示
-----------------------------------
![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233138_66acc47c_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233150_79627fa7_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233200_33d385db_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233211_5e7fc693_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233222_8ab40914_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233239_ebb4d8bb_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233252_11c11f7d_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233303_da10ce13_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233314_7bcc9728_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233324_44fbe21c_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233335_358d1208_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233347_79912823_1394985.png "在这里输入图片标题")

![输入图片说明](https://git.oschina.net/uploads/images/2017/0711/233356_3b2a0c61_1394985.png "在这里输入图片标题")


## 感谢
@baomidou
mybatis 增强工具包，简化 CRUD 操作
https://git.oschina.net/baomidou/mybatis-plus
