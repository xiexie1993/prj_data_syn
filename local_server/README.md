
## 一、概述

###  1、 编写目的

+  为项目的系统的开发设计的依据与指导。
+  为参与该项目的编程人员提供依据；
+  为修改、维护提供条件；  
+  项目负责人将按计划书的要求布置和控制开发工作全过程；  
+  项目质量保证组将按此计划书做阶段性和总结性的质量验证和确认。

### 2、 读者对象

+  项目开发人员，特别是编程人员；
+  软件维护人员；
+  技术管理人员；
+  执行软件质量保证计划的专门人员；   
+  参与本项目开发进程各阶段验证、确认以及负责为最后项目验收、鉴定提供相应报告的有关人员。
+  合作各方有关部门的负责人；项目组负责人和全体参加人员。

###  3、 注意事项

+  权限审查：此文档仅供技术部功能组内部使用。
+  保存备份：此文档仅在服务器上作修改，不允许本地备份。
+  该文档采用 markdown 编写规范，建议使用markdownPad或相关编辑工具查看和修改。


## 二、 项目说明


## 三、 代码说明

### 1、 代码框架 


> 注：

### 2、代码目录结构

~~~

project  应用部署目录
├─ 
└─ README.md            自述文件（帮助文档）

~~~

> 
> 
> 


### 3、命名规范

遵循PSR-2命名规范和PSR-4自动加载规范，并且注意如下规范：

+ 目录和文件
    *   目录不强制规范，驼峰和小写+下划线模式均支持；
    *   类的文件名均以命名空间定义，并且命名空间的路径和类库文件所在路径一致；
    *   类名和类文件名保持一致，统一采用驼峰法命名（首字母大写）；



+ 函数和类、属性命名

    *   类的命名采用驼峰法，并且首字母大写，例如 `User`、`UserType`，默认不需要添加后缀，例如`UserController`应该直接命名为`User`；
    *   函数的命名使用小写字母和下划线（小写字母开头）的方式，例如 `get_client_ip`
    *   方法的命名使用驼峰法，并且首字母小写，例如 `getUserName`
    *   属性的命名使用驼峰法，并且首字母小写，例如 `tableName`、`instance`
    *   以双下划线“__”打头的函数或方法作为魔法方法，例如 `__call` 和 `__autoload`


+ 常量和配置
    *   常量以大写字母和下划线命名，例如 `APP_PATH`和 `THINK_PATH`；
    *   配置参数以小写字母和下划线命名，例如 `url_route_on` 和`url_convert`；


+ 数据表和字段
    *   数据表和字段采用小写加下划线方式命名，并注意字段名不要以下划线开头，例如 `think_user` 表和 `user_name`字段，不建议使用驼峰和中文作为数据表字段命名。


## 开发

#### 战略

+ 登陆验证机制
    * 方案：用户认证用jwt

+ api文档生成
    * 方案：根据注释代码生成api文档html页面

+ 长连接方案
    * 方案：

+ 缓存
    * 方案： memcache、redis、squid、varnish、web cache、 CDN等
    * 参考资料
        + [各种缓存介绍](https://blog.csdn.net/Jesse_cool/article/details/76174778)
+ 数据库
    + 方案：MySQL 或 MariaDB


#### 战术



#### 依赖包安装及使用说明
