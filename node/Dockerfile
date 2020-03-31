FROM alpine:3.11

LABEL version="1.0" maintainer="Alexandre Servian <alexandreservian@gmail.com>"

ENV WORKSPACE=/usr/src/workspace

RUN apk add --update nodejs && mkdir -p ${WORKSPACE}

WORKDIR ${WORKSPACE}

VOLUME ${WORKSPACE}

CMD [ "node" ]