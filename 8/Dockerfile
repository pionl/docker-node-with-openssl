FROM node:8

MAINTAINER Martin Kluska <martin@kluska.cz>

RUN apt-get update \
	&& apt-get install -y openssl \
	&& rm -rf /var/lib/apt/lists/* \
	&& rm -rf /var/cache/apt/*
