FROM ubuntu:16.10

MAINTAINER Congying <congying1112@gmail.com>

RUN apt-get update && apt-get -y upgrade

RUN apt-get install -y python3.5-dev


RUN apt-get install -y wget
RUN ln -s /usr/bin/python3.5 /usr/bin/python
RUN wget https://bootstrap.pypa.io/get-pip.py && python get-pip.py