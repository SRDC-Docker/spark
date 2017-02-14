### Scala Dockerfiles

Spark Dockerfiles based on srdc/scala

### Base Docker Image

* [srdc/scala](https://hub.docker.com/r/srdc/scala/)


### Docker Tags

* `latest` (default): Spark 2.1.0 (alias to `2.1.0`)
* `2.1.0`: Spark 2.1.0 with Scala 2.11.7 as base
* `1.6.0`: Spark 1.6.0 with Scala 2.10.6 as base

### Installation
Execute either of the following:

    docker pull srdc/spark:tag       [downloads the image from Docker Hub]
    docker build -t srdc/spark:tag   [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/spark:tag
