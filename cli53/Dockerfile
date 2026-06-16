FROM alpine:3.24.1

RUN apk --no-cache add \
	ca-certificates \
	python \
	py2-pip \
	&& pip install cli53

ENTRYPOINT [ "cli53" ]
