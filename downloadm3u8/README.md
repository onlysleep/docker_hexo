# downloadm3u8
[中文](./README_zh_CN.md)  [English](./README.md)
## 简介
利用github action不断的构建可以用于downloadm3u8的最新python3 docker镜像，并且发布到dockerhub
频率是北京时间每周一的早上8.30

## 镜像包括以下软件及配置
- downloadm3u8 


## 使用方法
首先下载最新版docker镜像
```bash
docker pull xyzzpwn/downloadm3u8
```

然后使用下面的命令
```bash
docker run -it --rm xyzzpwn/downloadm3u8 bash
```
