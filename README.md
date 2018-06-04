# 基于官方的python镜像制作一个简单的python web服务镜像

----------------------------

## 拉取镜像

> docker pull seekplum/python2.7-web

## 启动容器
```bash
docker run -d \
-p 5000:80 \
--name python2.7-web \
seekplum/python2.7-web
```

## 浏览器访问
> IP:5000 
