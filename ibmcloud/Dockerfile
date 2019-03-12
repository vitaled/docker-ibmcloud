FROM alpine:3.9.2
LABEL Daniele Vitale "vitaled@gmail.com"

RUN apk add --update \
    curl \
    && rm -rf /var/cache/apk/*

RUN  curl -fsSL https://clis.cloud.ibm.com/install/linux | sh


