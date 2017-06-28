### 简介
[`LNMP`](https://github.com/nineyang/docker-for-lnmp)包含了`mysql:5.7`，`nginx:1.1`，`php:7.1`以及`php`的相关扩展，[GitHub](https://github.com/nineyang/docker-for-lnmp)地址:`https://github.com/nineyang/docker-for-lnmp`。
### 操作
`git clone`下来之后`cd`到该目录下并执行
```
docker-compose up --build -d
```
#### 停止容器
```
docker-compose stop
```
#### 重新开启容器
```
docker-compose start
```
#### 删除容器
```
docker-compose down
```
#### 安装php扩展
php扩展主要根据docker提供的docker-php-ext-install来安装，非常方便，[查看例子](https://github.com/nineyang/docker-for-lnmp/blob/master/docker/php/DockerFile)

#### 访问
浏览器输入localhost:8888
