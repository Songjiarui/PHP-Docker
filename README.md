# PHP-Docker
使用docker-compose配置的PHP本地运行环境
# 使用方式
克隆后，在目录执行```docker-compose up```。执行后会生成```application/``` ```data/```，分别为web根目录和数据库文件目录。

```config/site.conf```为nginx配置文件，可以修改站点目录。

需要安装PHP扩展，可以参考<https://hub.docker.com/_/php>在```dockerfiles/Dockerfile-php```中修改。
