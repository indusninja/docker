FROM ruby:alpine

MAINTAINER Prakash Prasad "prakash@prakashprasad.com"

# Update aptitude with new repo information
RUN apk update

# Install dependencies
RUN apk --no-cache add \
	build-base \
	gcc \
	bash \
	cmake \
	git

RUN gem install jekyll

ARG JEKYLL_PORT=5000

EXPOSE $JEKYLL_PORT

WORKDIR /site