FROM node:21.6.1-alpine
ARG DAEMON_WORKDIR
WORKDIR ${DAEMON_WORKDIR}

ENV TZ Asia/Tokyo

RUN apk update
RUN apk upgrade
RUN apk add git vim