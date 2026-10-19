# Docker

> 轻量级虚拟化容器。学网安的人用它搭靶场、跑工具、隔离环境，几乎每个安全实验平台都基于容器。

## 为什么学

- **搭靶场**：DVWA、pikachu 等漏洞环境一条命令启动；
- **隔离环境**：分析恶意样本、跑不信任的工具时，容器是常用隔离手段之一（注意：容器并非强隔离，恶意代码分析仍需用专用虚拟机）；
- **学习基础设施**：本地跑数据库、中间件、微服务都变得极简单。

## 核心概念

- **镜像（Image）**：只读模板（如 `ubuntu:22.04`）
- **容器（Container）**：镜像的运行实例
- **Dockerfile**：描述如何构建镜像
- **数据卷（Volume）**：容器间/宿主机持久化数据

## 常用命令

- `docker pull <镜像>` / `docker run -it <镜像> bash`
- `docker ps` / `docker stop <容器>` / `docker rm <容器>`
- `docker build -t <名字> .`
- `docker compose up -d`（多容器编排，靶场常用）

## 推荐资源

| 资源 | 类型 | 说明 |
| ---- | ---- | ---- |
| [Docker 官方文档](https://docs.docker.com/) | 文档 | 权威手册 |
| [Docker 入门教程（菜鸟教程）](https://www.runoob.com/docker/docker-tutorial.html) | 教程 | 中文快速上手 |
| [Play with Docker](https://labs.play-with-docker.com/) | 在线环境 | 浏览器里练 Docker |

## 学习建议

- 大二开始用 Docker 搭课程实验环境，能省大量「装环境」的时间；
- 学会写 Dockerfile 和 docker-compose.yml，后面玩靶场会频繁用到。
