# docker
docker学习之路  

## 常用命令

```
docker pull mysql:5.7
docker run --name gm_dev -p 3306:3306 -e MYSQL_ROOT_PASSWORD=1236547890 -v /Users/uc10d/workspaces/docker/gm_dev:/data -d mysql:5.7
```

## 熟练度

初级. 使用, 修改, 制作简单的Dockerfile

## 学习资料

* [我能用docker为我做什么](https://github.com/UC10D/docker/wiki/docker_lv)

* [docker入门到实践](https://yeasy.gitbooks.io/docker_practice/content/introduction/)

* [极客学院docker wiki](http://wiki.jikexueyuan.com/list/docker/)

* boyi 陈强精简版

## 仓库

* [Docker Hub](https://hub.docker.com/)

## demo

* boyi 老王
* [如何构建基于docker的开发环境](https://www.jianshu.com/p/29c422ae7c58)

## bug

* [docker制作镜像 apt-get 安装文件报错debconf: unable to initialize frontend: Dialog](http://blog.csdn.net/a19891024/article/details/78250967)
