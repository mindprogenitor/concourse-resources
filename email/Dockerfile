FROM alpine:edge

RUN apk --no-cache add bash email jq && sed -i "s/SIGNATURE_FILE/# SIGNATURE_FILE/" /etc/email/email.conf

ADD check /opt/resource/check
ADD in /opt/resource/in
ADD out /opt/resource/out

RUN chmod +x /opt/resource/*
