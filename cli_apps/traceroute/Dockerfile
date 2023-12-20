FROM alpine:latest
LABEL maintainer "Lakshy Sharma <lakshy1106@protonmail.com>"

RUN apk update && \
	apk add traceroute && \
	apk cache clean

ENTRYPOINT ["traceroute"]
