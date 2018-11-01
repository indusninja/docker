FROM alpine

MAINTAINER Prakash Prasad "prakash@prakashprasad.com"

# Update aptitude with new repo information
RUN apk update

# Install dependencies
RUN apk --no-cache add \
	git \
	cmake \
	make \
	g++
