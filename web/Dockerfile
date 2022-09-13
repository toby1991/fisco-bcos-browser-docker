From nginx:1.15.9-alpine

MAINTAINER Toby <me@tobyan.com>


WORKDIR /tmp
RUN apk add git
RUN git clone --depth=1 https://github.com/FISCO-BCOS/fisco-bcos-browser.git && \
    cd fisco-bcos-browser && \
    mkdir -p /data/app/web/ && \
    mv web/fisco-bcos-browser-front/* /data/app/web/
