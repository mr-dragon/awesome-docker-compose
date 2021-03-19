# Awesome Docker Compose [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![logo](awesome-compose.jpg)

## Docker Compose概述

[官方：帆樯 -> Docker Compose 概述](https://docs.docker.com/compose/)

## 新增Docker Compose====Start

- Kafka
- mariadb
- gitea

### 主要是开发环境

## 新增Docker Compose====End

## 官方Docker Compose仓库说明====Start

**以下内容翻自 [官方 Docker Compose 仓库说明](https://github.com/docker/awesome-compose/blob/master/README.md)**

---

> 精选的 Docker Compose示例列表。

这些样本为如何使用Compose文件集成不同的服务以及如何使用Docker Compose管理它们的部署提供了一个起点。

> **注意:**
>
> 以下示例旨在用于本地开发环境中，例如项目设置，修补软件堆栈等。这些示例不得部署在生产环境中。

<!--lint disable awesome-toc-->
## 目录

- [具有多个集成服务的Docker Compose应用程序样本](#具有多个集成服务的Docker Compose应用程序样本).
- [单一服务样本](#单一服务样本).
- [不同平台的基本设置（不适用于生产环境-供个人使用）)](#不同平台的基本设置（不适用于生产环境-供个人使用）).

## 具有多个集成服务的Docker Compose应用程序样本

- [`ASP.NET / MS-SQL`](https://github.com/docker/awesome-compose/tree/master/aspnet-mssql) - Sample ASP.NET core application
with MS SQL server database.
- [`Elasticsearch / Logstash / Kibana`](https://github.com/docker/awesome-compose/tree/master/elasticsearch-logstash-kibana) - Sample Elasticsearch, Logstash, and Kibana stack.
- [`Go / NGINX / MySQL`](https://github.com/docker/awesome-compose/tree/master/nginx-golang-mysql) - Sample Go application
with an Nginx proxy and a MySQL database.
- [`Go / NGINX / PostgreSQL`](https://github.com/docker/awesome-compose/tree/master/nginx-golang-postgres) - Sample Go
application with an Nginx proxy and a PostgreSQL database.
- [`Java Spark / MySQL`](https://github.com/docker/awesome-compose/tree/master/sparkjava-mysql) - Sample Java application and
a MySQL database.
- [`NGINX / Flask / MongoDB`](https://github.com/docker/awesome-compose/tree/master/nginx-flask-mongo) - Sample Python/Flask
application with Nginx proxy and a Mongo database.
- [`NGINX / Flask / MySQL`](https://github.com/docker/awesome-compose/tree/master/nginx-flask-mysql) - Sample Python/Flask
application with an Nginx proxy and a MySQL database.
- [`NGINX / Go`](https://github.com/docker/awesome-compose/tree/master/nginx-golang) - Sample Nginx proxy with a Go backend.
- [`React / Spring / MySQL`](https://github.com/docker/awesome-compose/tree/master/react-java-mysql) - Sample React
application with a Spring backend and a MySQL database.
- [`React / Express / MySQL`](https://github.com/docker/awesome-compose/tree/master/react-express-mysql) - Sample React
application with a Node.js backend and a MySQL database.
- [`React / Rust / PostgreSQL`](https://github.com/docker/awesome-compose/tree/master/react-rust-postgres) - Sample React
application with a Rust backend and a Postgres database.
- [`Spring / PostgreSQL`](https://github.com/docker/awesome-compose/tree/master/spring-postgres) - Sample Java application
with Spring framework and a Postgres database.  

## 单一服务样本

- [`Angular`](https://github.com/docker/awesome-compose/tree/master/angular)
- [`Spark`](https://github.com/docker/awesome-compose/tree/master/sparkjava)
- [`VueJS`](https://github.com/docker/awesome-compose/tree/master/vuejs)
- [`Flask`](https://github.com/docker/awesome-compose/tree/master/flask)
- [`PHP`](https://github.com/docker/awesome-compose/tree/master/apache-php)
- [`Traefik`](https://github.com/docker/awesome-compose/tree/master/traefik-golang)
- [`Django`](https://github.com/docker/awesome-compose/tree/master/django)
- [`Minecraft server`](https://github.com/docker/awesome-compose/tree/master/minecraft)

## 不同平台的基本设置（不适用于生产环境-供个人使用）

- [`Gitea / PostgreSQL`](https://github.com/docker/awesome-compose/tree/master/gitea-postgres)
- [`Nextcloud / PostgreSQL`](https://github.com/docker/awesome-compose/tree/master/nextcloud-postgres)
- [`Nextcloud / Redis / MariaDB`](https://github.com/docker/awesome-compose/tree/master/nextcloud-redis-mariadb)
- [`Wordpress / MySQL`](https://github.com/docker/awesome-compose/tree/master/wordpress-mysql)
- [`Prometheus / Grafana`](https://github.com/docker/awesome-compose/tree/master/prometheus-grafana)

<!--lint disable awesome-toc-->
## 入门指南

这些说明将指导您完成创建和引导的引导阶段。
使用Docker Compose部署容器化应用程序的样本。

### 先决条件

- 确保已安装Docker和Docker Compose
  - Windows or macOS:
    [Install Docker Desktop](https://www.docker.com/get-started)
  - Linux: [Install Docker](https://www.docker.com/get-started) and then
    [Docker Compose](https://github.com/docker/compose)
- 从此存储库下载一些或所有样本。

### 运行样本

每个样本的根目录包含`docker-compose.yaml`，其中
描述服务组件的配置。所有样品均可在
通过进入每个目录的根目录并执行以下命令来创建本地环境：

```console
docker-compose up -d
```

检查每个样本的`README.md`以获取有关结构和结构的更多详细信息。
什么是预期的输出。
要停止并删除示例应用程序运行的所有容器，请执行以下操作：

```console
docker-compose down
```

<!--lint disable awesome-toc-->
## 贡献

我们欢迎一些示例，这些示例可以帮助人们了解如何将Docker Compose用于
常见的应用程序。 点击 [贡献指南](CONTRIBUTING.md) 查看更多细节.

## 官方Docker Compose仓库说明====End
