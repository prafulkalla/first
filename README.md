FROM ubuntu:16.04
MAINTAINER Praful Kalla <praful.kalla@gmail.com>

RUN apt-get update && apt-get install curl \
            nmap htop

ENTRYPOINT ["ping"]
