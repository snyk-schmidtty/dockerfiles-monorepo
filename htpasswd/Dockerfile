FROM alpine:3.24.1
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk add --no-cache \
	apache2-utils

ENTRYPOINT [ "htpasswd" ]
