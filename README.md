### Scala Dockerfiles

Scala Dockerfiles based on srdc/java

### Base Docker Image

* [srdc/java:oraclejdk-8](https://hub.docker.com/r/srdc/java/)


### Docker Tags

* `latest` (default): Oracle JDK 8 (alias to `oraclejdk-8`)
* `2.11.7`: Scala 2.11.7
* `2.10.6`: Scala 2.10.6

### Installation
Execute either of the following:

    docker pull srdc/scala:tag       [downloads the image from Docker Hub]
    docker build -t srdc/scala:tag   [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/scala:tag
