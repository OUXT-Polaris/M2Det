FROM nvidia/cuda:10.0-cudnn7-devel-ubuntu18.04

RUN apt-get update
RUN apt-get -y install git wget python python-pip
RUN git clone https://github.com/qijiezhao/M2Det.git
WORKDIR M2Det
RUN pip install -r requirements.txt