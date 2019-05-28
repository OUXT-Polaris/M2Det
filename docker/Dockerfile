FROM nvidia/cuda:10.0-cudnn7-devel-ubuntu18.04

RUN apt-get update
RUN apt-get -y install git wget python3 python3-pip
RUN git clone https://github.com/OUXT-Polaris/M2Det.git
WORKDIR M2Det
RUN git checkout feature/docker 
RUN pip3 install -r requirements.txt