FROM nginx:1.17-alpine

RUN apk add --no-cache curl

COPY ./conf.d /etc/nginx/conf.d

WORKDIR /app