### Apache Spark Dockerfile

Apache Spark Dockerfile based on srdc/scala

### Base Docker Image

* [srdc/scala:2.11.7](https://hub.docker.com/r/srdc/scala/)


### Installation
Execute either of the following:

    docker pull srdc/spark:2.1.0  (latest)  [downloads the image from Docker Hub]
    docker build -t srdc/spark:2.1.0        [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/spark:2.1.0
