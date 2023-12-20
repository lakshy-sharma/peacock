FROM python:3-alpine3.18
LABEL maintainer "Lakshy Sharma <lakshy1106@protonmail.com>"

RUN apk update && \
	apk add ca-certificates && \
	pip3 install awscli && \
	mkdir -p /root/.aws && \
	{ \
		echo '[default]'; \
		echo 'output = json'; \
		echo 'region = $AWS_DEFAULT_REGION'; \
		echo 'aws_access_key_id = $AWS_ACCESS_KEY_ID'; \
		echo 'aws_secret_access_key = $AWS_SECRET_ACCESS_KEY'; \
	} > /root/.aws/config
ENTRYPOINT ["aws"] 