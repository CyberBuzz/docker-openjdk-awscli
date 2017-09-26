FROM openjdk:8

MAINTAINER Taka Sasaki <sasaki_taka@cyberbuzz.co.jp>

RUN apt-get update && apt-get install -y python-pip && \
    pip install awscli && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*