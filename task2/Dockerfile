FROM ubuntu:18.04

RUN apt-get update
RUN apt-get -y install python3.6

ADD app/ /app
WORKDIR /app

EXPOSE 8080

CMD python3.6 /app/server.py
