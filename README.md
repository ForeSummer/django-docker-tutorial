## django-docker-tutorial

*《软件工程》，清华大学软件学院*

Docker + Django + Mysql + Ngnix + Gunicorn 的示例，帮助同学们快速理解Docker以及docker-compose的使用

### 安装Docker

[Docker-从入门到实践](https://yeasy.gitbook.io/docker_practice/install)

### 启动项目

```bash
# -d 后台运行
# --build 重新构建image
docker-compose up -d --build
```

### 停止项目

```bash
docker-compose down
```

### 构建镜像

```bash
# -t 命名与tag
# . 表示context是当前目录
docker build -t django-test:v1.0.0 .
```

