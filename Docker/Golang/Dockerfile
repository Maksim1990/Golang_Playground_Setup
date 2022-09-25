FROM golang:latest

ADD . /go/src/github.com/goPlayground

RUN apt-get update
RUN apt-get install vim -y

# # Set entrypoint
# RUN cd /go/src/github.com/goPlayground

WORKDIR /go/src/github.com/goPlayground

# Expose default port (9090)
EXPOSE 9090

