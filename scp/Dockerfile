FROM alpine:edge

RUN apk --no-cache add bash openssh

ADD check /opt/resource/check
ADD in /opt/resource/in
ADD out /opt/resource/out

RUN chmod +x /opt/resource/*
