# 简介
这个项目是学习hyperf时编写的可能会适合一些刚学习hyperf的同学参考。项目中也使用了很多hyperf的基础功能和组件。  

# 系统要求

 - PHP >= 7.2
 - Swoole PHP 扩展 >= 4.4 并且关闭 `Short Name`
 - OpenSSL PHP 扩展
 - JSON PHP 拓展
 - PDO PHP 拓展 
 - Redis PHP 拓展 
 - Protobuf PHP 拓展
 - ElasticSearch >= 7.0

# 安装

安装组件  
`composer install`

执行数据库迁移  
`php bin/hyperf.php migrate --seed`

执行ElasticSearch索引迁移  
`php bin/hyperf.php es:migrate`

执行同步商品到ElasticSearch命令  
`php bin/hyperf.php es:sync-products`

启动  
`php watch`

