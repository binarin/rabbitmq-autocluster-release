FROM debian:jessie

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update \
 && apt-get install -y --no-install-recommends erlang-nox erlang-src erlang-dev debhelper git rsync fakeroot build-essential python zip \
 && apt-get clean
