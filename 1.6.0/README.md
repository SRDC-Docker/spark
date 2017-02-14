### Apache Spark Dockerfile

Apache Spark Dockerfile based on srdc/scala

### Base Docker Image

* [srdc/scala:2.10.6](https://hub.docker.com/r/srdc/scala/)


### Installation
Execute either of the following:

    docker pull srdc/spark:1.6.0  [downloads the image from Docker Hub]
    docker build -t srdc/spark:1.6.0        [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/spark:1.6.0
