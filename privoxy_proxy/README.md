# privoxy_proxy
[中文](./README_zh_CN.md)  [English](./README.md)
## 简介
利用github action不断的构建可以用于代理socks5的最新privoxy docker镜像，并且发布到dockerhub
频率是北京时间每周一的早上8.30

## 镜像包括以下软件及配置
- privoxy

## 使用方法
首先下载最新版docker镜像
```bash
docker pull xyzzpwn/privoxy_proxy
```

然后使用下面的命令
```bash
docker run -it --rm -p 8888:8118 -e "address=ip:port" xyzzpwn/privoxy_proxy
```

指定ip
```bash
docker run -it --rm -p 8888:8118 -e "address=ip:port" -e "allowip=ip" xyzzpwn/privoxy_proxy
```