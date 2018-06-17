# Springboot的学习记录

此代码库主要记录本人对Springboot的学习步骤及思路。

### [study01](http://www.zslin.com/web/article/detail/7)

+ 一个简单的HelloWorld级的应用例子
+ 可正常运行，只是了解Springboot的搭建步骤
+ 使用IDEA开发工具，以Maven方式搭建的Springboot应用

### [study02](http://www.zslin.com/web/article/detail/11)

使用Controller的方式：

+ 讲述Springboot中读取核心配置文件的两种方法
+ 讲述Springboot读取自定义配置文件的方法

### [study03](http://www.zslin.com/web/article/detail/12)

使用单元测试的方式：

+ 讲述Springboot中读取核心配置文件的两种方法
+ 讲述Springboot读取自定义配置文件的方法

### [study04](http://www.zslin.com/web/article/detail/14)

主要描述在Springboot的单元测试和项目启动时如何使用不同的配置文件，功能不多，搞清楚原理即可。

### [study05](http://www.zslin.com/web/article/detail/15)

引入Mysql数据库，引入Jpa管理数据库，使用Hibernate自动建表。

### [study06](http://www.zslin.com/web/article/detail/16)

使用Jpa对数据库进行增加、删除、修改和查询，全部使用`JpaRepository`接口的方法实现。

### [study07](http://www.zslin.com/web/article/detail/17)

+ 使用Spring Data Jpa的特性对数据库进行相关操作
+ 介绍使用表达式查询的一些常用关键字
+ 使用Hql对数据库进行操作
+ 介绍使用Hql对数据库操作时的两种参数传递方式

### [study08](http://www.zslin.com/web/article/detail/18)

使用JPA对数据进行排序

1. 使用原生进行排序
2. 封装单一排序方式
3. 封装任意多个排序条件的方式排序

### [study09](http://www.zslin.com/web/article/detail/19)

使用JPA对数据进行分页

1. 使用原生方式分页测试
2. 封装分页功能，并与上一讲中的排序进行整合

多个分页重载方法足以满足绝大多数的需求


### [study10](http://www.zslin.com/web/article/detail/20)

1. 单一筛选条件测试筛选
2. 封装筛选功能及新增几个工具类
3. 通过封装解决多条件测试数据筛选功能

### [study11](http://www.zslin.com/web/article/detail/21)

使用Scheduled做定时任务

### [study12](http://www.zslin.com/web/article/detail/22)

JavaMailSender发送电子邮件

+ 以163邮箱发送邮件
+ 以QQ邮箱发送邮件
+ 发送HTML格式的邮件
+ 设置收件人显示的发件人名称

### [study13](http://www.zslin.com/web/article/detail/23)

  静态资源路径配置

+ 配置路径信息
+ 通过文件上传方式测试路径是否生效
+ 通过浏览器方式验证能否访问路径中的文件

### [study14](http://www.zslin.com/web/article/detail/28)

  POI导出Word文件

+ 使用POI导出Word文件
+ 模板文件放在`classpath`中的导出实现

### [study15](http://www.zslin.com/web/article/detail/29)

  POI对Excel的读取操作

+ 使用POI读取Excel文件

### [study16](http://www.zslin.com/web/article/detail/30)

  POI导出Excel文件

+ 使用POI导出Excel文件
+ 自动生成表结构
+ 自动替换常量属性

### [study17](http://www.zslin.com/web/article/detail/34)

[Springboot](http://www.zslin.com/?cateId=3)+[Thymeleaf](http://www.zslin.com/?cateId=5)实现多文件上传