FROM node:alpine

MAINTAINER Martin Kluska <martin@kluska.cz>

RUN apk update \
	&& apk add --no-cache openssl\
	&& rm -rf /var/lib/apt/lists/* \
	&& rm -rf /var/cache/apk/*
