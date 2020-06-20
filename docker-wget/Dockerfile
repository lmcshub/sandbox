# A simple wget container

FROM alpine

LABEL VERSION=0.1 \
      AUTHOR=LMCS \
      EMAIL=lmcsdeveloper@gmail.com

RUN apk update \
 && apk add wget \
 && rm -rf /var/cache/apk/*

WORKDIR /root/

ENTRYPOINT [ "wget" ]

CMD [ "--help" ]

