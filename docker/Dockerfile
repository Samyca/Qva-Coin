FROM debian:stretch
LABEL maintainer="Juan Darien Macías Hernández <contact@samyca.com>"
LABEL description="Dockerised Qva Coin, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
