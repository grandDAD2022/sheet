# syntax=docker/dockerfile:1
# Nginx Docker for `sheet`

FROM alpine

RUN apk update && \
	apk upgrade && \
	apk add nginx nginx-mod-http-vts

ENTRYPOINT nginx -g 'daemon off;'
