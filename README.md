# Hadoop + Hive + PostgreSQL + Jupyter w/ pyspark Dockerized Setup

This repository provides a **Docker Compose** setup for running a local development stack consisting of:

* **Hadoop** (NameNode + DataNode)
* **Apache Hive** (with HiveServer2 + Metastore)
* **PostgreSQL** (as Hive Metastore)
* **Jupyter Notebook + pyspark** (as UI for interacting with Spark)

> ⚠️ This setup is **intended for development and testing purposes**. It is **not production-ready**.

## Fast Deploy

### Prerequesties

* git
* docker, docker-compose

```bash
git clone git@github.com:gndvrn/Hadoop-Hive-Spark-Local-Deploy-via-Docker.git
cd Hadoop-Hive-Spark-Local-Deploy-via-Docker
docker-compose up -d
```

## Ports

* `localhost:8888` - Jupyter Notebook
* `localhost:9870` - Hadoop NameNode UI
* `localhost:9864` - Hadoop DataNode UI
* `localhost:10002` - Hive Metastore Thrift
