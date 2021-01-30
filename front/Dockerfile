FROM node:14.15.4-alpine3.10

RUN apk update \
    && npm install -g npm @vue/cli \
    && yarn install

WORKDIR /app

EXPOSE 8080