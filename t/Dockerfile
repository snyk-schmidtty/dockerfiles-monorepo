FROM	ruby:3.4.7-alpine3.22
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN	apk add --no-cache \
	ca-certificates

RUN	set -x \
	&& apk add --no-cache --virtual .build-deps \
	build-base \
	&& gem install io-console t --no-document \
	&& apk del .build-deps

ENTRYPOINT	["t"]
