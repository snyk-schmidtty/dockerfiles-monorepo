FROM alpine:3.23.4
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	bash \
	certbot

ENTRYPOINT [ "certbot" ]
