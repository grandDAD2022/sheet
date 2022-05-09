FROM alpine

RUN apk update && \
	apk upgrade && \
	apk add nginx nginx-mod-http-vts

ENTRYPOINT nginx -g 'daemon off;'
