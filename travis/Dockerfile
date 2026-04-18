FROM	ruby:4.0.2-alpine3.23
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN	apk add --no-cache \
	ca-certificates \
	git

RUN	set -x \
	&& apk add --no-cache --virtual .build-deps \
	build-base \
	&& gem install travis --no-document \
	&& apk del .build-deps

ENTRYPOINT	["travis"]
