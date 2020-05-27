FROM ubuntu:18.04

RUN apt-get update
RUN apt-get -y install python3.6

VOLUME [/data]
WORKDIR /data

EXPOSE 8080

CMD python3.6 /data/server.py
