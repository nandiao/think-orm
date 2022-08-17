# ThinkORM(nandiao fork修改版)
修改内容
* 添加对swoole多协程的支持 修改版本:2c1382a
* [修复在使用model时不能使用group方法的问题](https://github.com/top-think/think-orm/pull/300)



基于PHP7.1+ 和PDO实现的ORM，支持多数据库，2.0版本主要特性包括：

* 基于PDO和PHP强类型实现
* 支持原生查询和查询构造器
* 自动参数绑定和预查询
* 简洁易用的查询功能
* 强大灵活的模型用法
* 支持预载入关联查询和延迟关联查询
* 支持多数据库及动态切换
* 支持`MongoDb`
* 支持分布式及事务
* 支持断点重连
* 支持`JSON`查询
* 支持数据库日志
* 支持`PSR-16`缓存及`PSR-3`日志规范


## 安装
~~~
composer require topthink/think-orm
~~~

## 文档

详细参考 [ThinkORM开发指南](https://www.kancloud.cn/manual/think-orm/content)
