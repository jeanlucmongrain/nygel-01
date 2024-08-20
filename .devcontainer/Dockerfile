# https://hub.docker.com/_/golang
FROM golang:1.23.0-alpine3.20
RUN apk add git openssh-client htop
COPY github.pub /etc/ssh/ssh_known_hosts
