FROM ubuntu:bionic
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
	apt-get install -y build-essential gcc g++ pkg-config \
		cmake python-pip git-core ccache \
		libftdi-dev zlib1g-dev libusb-1.0-0-dev \
		libdc1394-22-dev libjpeg-dev libopencv-dev \
		libgtest-dev libeigen3-dev libsuitesparse-dev \
		libopenni2-dev libudev-dev libboost-python-dev \
		libpython-dev python-numpy libpcl-dev curl

