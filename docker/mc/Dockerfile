FROM ubuntu:20.04
ENV DEBIAN_FRONTEND noninteractive
RUN apt update && \
    apt upgrade -y && \
    apt install -y wget tzdata openjdk-17-jre-headless
ENV TZ Asia/Tokyo
