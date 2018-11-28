FROM debian:stretch
LABEL maintainer="Soxar Developers <dev@soxar.org>"
LABEL description="Dockerised SoxarCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
