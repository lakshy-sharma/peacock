FROM alpine:3.18
LABEL maintainer "Lakshy Sharma <lakshy1106@protonmail.com>"

RUN apk update && \
	apk add tcpdump && \
	apk cache clean

ENTRYPOINT ["tcpdump"]
