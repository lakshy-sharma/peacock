include $(PWD)/.env

build_and_push:
	REPO_NAME=$(REPO_NAME) VERSION=$(VERSION) docker-compose build --parallel;
	REPO_NAME=$(REPO_NAME) VERSION=$(VERSION) docker-compose push;