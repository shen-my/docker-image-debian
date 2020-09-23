FROM debian:buster-slim

RUN apt-get update && apt-get install -y apt-transport-https ca-certificates

COPY sources.list /etc/apt/sources.list

RUN apt-get update && \
    apt-get install -y wget
