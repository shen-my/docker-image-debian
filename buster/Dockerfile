FROM debian:buster-slim

RUN apt-get update && apt-get install -y apt-transport-https ca-certificates apt-utils

COPY sources.list /etc/apt/sources.list

RUN apt-get update && \
    apt-get install -y wget procps

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
