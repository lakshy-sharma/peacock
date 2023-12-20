FROM debian:bookworm-slim
LABEL maintainer "Lakshy Sharma <lakshy1106@protonmail.com>"

RUN apt update && \
    apt upgrade -y && \
	DEBIAN_FRONTEND=noninteractive apt install tshark -y && \
	apt autoremove -y 

ENTRYPOINT ["tshark"]
