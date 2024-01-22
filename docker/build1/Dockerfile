FROM alpine:latest
MAINTAINER "osman@osman.com"
WORKDIR /mytext
COPY ./my.txt build1.txt

RUN apk add redis

ENTRYPOINT ["redis-server"]