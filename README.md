## GCC Build environment for CentOS Dockerfile


### Base Docker Image

* [centos:7](https://hub.docker.com/_/centos/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download : `docker pull oingo/gcc`


### Usage

    docker run -it -v <volume>:/root/project oingo/gcc /bin/bash
