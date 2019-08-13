FROM ubuntu:xenial

RUN apt-get update && \
	apt install -y software-properties-common && \
	add-apt-repository -y ppa:ubuntu-toolchain-r/test && \
	apt-get update && \
	apt-get install -y build-essential gcc-7 g++-7 clang pkg-config \
		cmake python-pip git-core ccache curl
