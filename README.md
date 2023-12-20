# Peacock: A Collection of Docker Containers for Daily Use. 

All containers provided here can be found openly on Dockerhub: https://hub.docker.com/search?q=sharmalakshy

These containers contain common CLI applications packaged such that you can run the CLI applications directly without installing them on your base system.

## CLI Applications
An assorted collection of handy cli tools packaged individually into micro-containers.

1. awscli
2. netcat
3. nmap
4. tcpdump
5. traceroute
6. tshark

### Usage

To use netcat you must do the following.

``docker run -it sharmalakshy/netcat <parameters>``

To use awscli you must try to make use of environment variables like as follows.

``docker run -e AWS_DEFAULT_REGION -e AWS_DEFAULT_REGION=us-east-1 -e AWS_ACCESS_KEY_ID=xyz -e AWS_SECRET_ACCESS_KEY=xyz -it sharmalakshy/awscli <args> <params>``

## GUI Applications
An assorted collection of handy gui applications packaged for easy use.

_Work Under Progress_
