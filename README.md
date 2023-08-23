# EverythingBaseDocker

```
日常使用的一些服务，写成docker-compose方便使用。存个档自己备用
```
# 数据库（DataBase）
## mysql_fastinit
```一个配置好快速恢复数据库配置```  
\Database\mysql\mysql_5.x_fastinit\
 ```bash 
使用方式
启动前保证数据'data'目录为空，将需要恢复的SQL文件放置于init目录下，docker-compose启动即可。
```
# web中间件 （WebServer）
