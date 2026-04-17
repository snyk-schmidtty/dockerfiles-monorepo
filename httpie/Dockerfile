FROM alpine:3.23.4
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	ca-certificates \
	python \
	py2-pip \
	&& pip install httpie httpie-unixsocket

ENTRYPOINT [ "http" ]
