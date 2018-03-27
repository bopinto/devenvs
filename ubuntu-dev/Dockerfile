FROM ubuntu

RUN apt-get update && apt-get install -y vim python git

RUN mkdir -p /opt/dev

COPY get-pip.py /opt/dev/get-pip.py

WORKDIR /opt/dev

RUN python get-pip.py