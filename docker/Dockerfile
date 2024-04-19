FROM ubuntu:latest

RUN apt-get update 

RUN apt-get install -y \
    git \
    python3 \
    python3-pip \
    python3-setuptools \
    python3-dev \
    build-essential \
    zlib1g-dev

RUN pip3 install --upgrade pip

WORKDIR /opt

RUN git clone https://github.com/deeptools/deepTools

WORKDIR /opt/deepTools

RUN pip install .
